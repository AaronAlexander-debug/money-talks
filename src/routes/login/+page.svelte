<div class="flex flex-col justify-center items-center pt-10 gap-5">
    <div class="flex flex-col gap-3 shadow-lg px-14 pb-20 bg-stone-100">
        <h1 class="font-medium text-center m-5 text-5xl p-10">Log In</h1>
        <form class="flex flex-col gap-5">
            <label for="username" class="sr-only">Username</label>
            <input
                id="username"
                name="username"
                type="text"
                required
                placeholder="Username"
                class="rounded-md"
            />
            <input
                id="password"
                name="password"
                type="text"
                required
                placeholder="Password"
                class="rounded-md"
            />
            <button
            type="submit"
            class="rounded-md bg-green-600 transition hover:bg-green-700 text-slate-50 p-2 px-4">
                Log In
            </button>
        </form>
    </div>
</div>