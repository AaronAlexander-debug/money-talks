<script>
import { goto } from '$app/navigation';

function goToFinancePage() {
    goto('/finance');
}

function goToDataPage() {
    goto('/data');
}

function goToSavingsPage() {
    goto('/savings');
}
</script>

<div class="flex flex-col justify-center items-center pt-10 gap-5">
    <h1 class="font-medium text-center m-5 text-5xl p-5">Hello, Username!</h1>
    <button on:click={goToFinancePage} class="rounded-md bg-green-600 transition hover:bg-green-700 text-slate-50 p-2 px-4">Add to Finance Tracker</button>
    <button on:click={goToDataPage} class="rounded-md bg-green-600 transition hover:bg-green-700 text-slate-50 p-2 px-4">View Data Trends</button>
    <button on:click={goToSavingsPage} class="rounded-md bg-green-600 transition hover:bg-green-700 text-slate-50 p-2 px-4">Update Savings Goal</button>
</div>