# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Hier ist der für ein Login-Menü:
´´´
<div class="flex min-h-screen items-center justify-center bg-gray-100 dark:bg-gray-900">
  <div class="w-full max-w-md space-y-6 rounded-lg bg-white p-8 shadow-lg dark:bg-gray-800">
    <div class="space-y-2 text-center">
      <h1 class="text-3xl font-bold tracking-tight">Welcome back</h1>
      <p class="text-gray-500 dark:text-gray-400">Enter your email and password to sign in.</p>
    </div>
    <form class="space-y-4">
      <div>
        <label
          class="text-sm font-medium leading-none peer-disabled:cursor-not-allowed peer-disabled:opacity-70"
          for="email"
        >
          Email
        </label>
        <input
          class="flex h-10 w-full rounded-md border border-input bg-background px-3 py-2 text-sm ring-offset-background file:border-0 file:bg-transparent file:text-sm file:font-medium placeholder:text-muted-foreground focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:cursor-not-allowed disabled:opacity-50"
          id="email"
          placeholder="m@example.com"
          required=""
          type="email"
        />
      </div>
      <div>
        <div class="flex items-center justify-between">
          <label
            class="text-sm font-medium leading-none peer-disabled:cursor-not-allowed peer-disabled:opacity-70"
            for="password"
          >
            Password
          </label>
          <a class="text-sm font-medium text-gray-900 hover:underline dark:text-gray-400" href="#" rel="ugc">
            Forgot password?
          </a>
        </div>
        <input
          class="flex h-10 w-full rounded-md border border-input bg-background px-3 py-2 text-sm ring-offset-background file:border-0 file:bg-transparent file:text-sm file:font-medium placeholder:text-muted-foreground focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:cursor-not-allowed disabled:opacity-50"
          id="password"
          required=""
          type="password"
        />
      </div>
      <button
        class="inline-flex items-center justify-center whitespace-nowrap rounded-md text-sm font-medium ring-offset-background transition-colors focus-visible:outline-none focus-visible:ring-2 focus-visible:ring-ring focus-visible:ring-offset-2 disabled:pointer-events-none disabled:opacity-50 bg-primary text-primary-foreground hover:bg-primary/90 h-10 px-4 py-2 w-full"
        type="submit"
      >
        Sign in
      </button>
    </form>
    <div class="text-center text-sm text-gray-500 dark:text-gray-400">
      Don't have an account?{" "}
      <a class="font-medium text-gray-900 hover:underline dark:text-gray-400" href="#" rel="ugc">
        Sign up
      </a>
    </div>
  </div>
</div>
´´´
