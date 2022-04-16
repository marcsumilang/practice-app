<script>
	import '$lib/styles/app.css';
</script>

<div class="drawer drawer-mobile">
	<input id="my-drawer-2" type="checkbox" class="drawer-toggle" />
	<div class="drawer-content flex flex-col">
		<!-- Page content here -->
		<label for="my-drawer-2" class="btn btn-primary drawer-button lg:hidden">Open drawer</label>
		<slot />
	</div>
	<div class="drawer-side">
		<label for="my-drawer-2" class="drawer-overlay" />
		<ul class="menu p-4 overflow-y-auto w-80 bg-neutral text-white">
			<!-- Sidebar content here -->
			<li><a href="/">Home</a></li>
			<li><a href="/about">About</a></li>
			<li><a href="/login">Login</a></li>
		</ul>
	</div>
</div>
