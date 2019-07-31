<script>
	import Navbar from "components/Navbar";
	import NavbarItem from "components/NavbarItem";
</script>

<svelte:head>
	<title>Nik Radi</title>
</svelte:head>

<Navbar>
	<span slot="brand">
		<NavbarItem href="/">Nik Radi</NavbarItem>
	</span>
	<span slot="items">
		<NavbarItem href="#about">About</NavbarItem>
		<NavbarItem href="#projects">Projects</NavbarItem>
		<NavbarItem href="#contact">Contact</NavbarItem>
	</span>
</Navbar>

<main>
	<slot></slot>
</main>