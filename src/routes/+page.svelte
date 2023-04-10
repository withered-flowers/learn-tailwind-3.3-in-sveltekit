<h1 class="text-3xl font-semibold underline">Hello Tailwind v3.3!</h1>

<main class="p-4">
	<h3 class="text-xl/loose font-semibold text-gray-700/90">Extended Color Palette</h3>
</main>

<main class="p-4 md:w-1/2 lg:w-1/3 w-full">
	<h3 class="text-xl/loose font-semibold text-gray-700/90">New Line Clamp without Plugin</h3>
	<article>
		<time>Mar 10, 2020</time>
		<h2>Boost your conversion rate</h2>
		<p class="line-clamp-4 text-base/5">
			Nulla dolor velit adipisicing duis excepteur esse in duis nostrud occaecat mollit incididunt
			deserunt sunt. Ut ut sunt laborum ex occaecat eu tempor labore enim adipisicing minim ad. Est
			in quis eu dolore occaecat excepteur fugiat dolore nisi aliqua fugiat enim ut cillum. Labore
			enim duis nostrud eu. Est ut eiusmod consequat irure quis deserunt ex. Enim laboris dolor
			magna pariatur. Dolor et ad sint voluptate sunt elit mollit officia ad enim sit consectetur
			enim.
		</p>
		<div>Lindsay Walton</div>
	</article>
</main>

<main class="p-4">
	<h3 class="text-xl/loose font-semibold text-gray-700/90">New Caption in Table Class</h3>
	<table class="border border-sky-400">
		<caption class="caption-bottom font-semibold text-sm">
			Table 3.1: Professional wrestlers and their signature moves.
		</caption>
		<thead class="border border-sky-400">
			<tr>
				<th class="py-2">Wrestler</th>
				<th>Signature Move(s)</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<td class="py-2 px-4">"Stone Cold" Steve Austin</td>
				<td class="py-2 px-4">Stone Cold Stunner, Lou Thesz Press</td>
			</tr>
			<tr>
				<td class="py-2 px-4">Bret "The Hitman" Hart</td>
				<td class="py-2 px-4">The Sharpshooter</td>
			</tr>
			<tr>
				<td class="py-2 px-4">Razor Ramon</td>
				<td class="py-2 px-4">Razor's Edge, Fallaway Slam</td>
			</tr>
		</tbody>
	</table>
</main>

<style lang="postcss">
	:global(html) {
		background-color: theme(colors.gray.100);
	}
</style>
