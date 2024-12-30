<script>
import { goto } from '$app/navigation';

function goToLoginPage() {
    goto('/login');
}

function goToSignupPage() {
    goto('/signup');
}
</script>

<div class="flex flex-col justify-content-center align-items-center pt-10 gap-5">
<h1 class="font-medium text-center text-5xl">MoneyTalks</h1>
<p class="text-2xl text-center">💸 Your favorite personal finance assistant! 💸</p>
</div>

<div class="flex flex-row justify-center gap-14 pt-5">
<button on:click={goToLoginPage} class="rounded-md bg-green-600 transition hover:bg-green-700 text-slate-50 p-2 px-4">Log In</button>
<button on:click={goToSignupPage} class="rounded-md bg-green-600 transition hover:bg-green-700 text-slate-50 p-2 px-4">Sign Up</button>
</div>
