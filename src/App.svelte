<script>
	import TopNav from './components/TopNav.svelte';
	import UserNav from './components/UserNav.svelte';
	import CategoryNav from './components/CategoryNav.svelte';
	import AnnouncementsNav from './components/AnnouncementsNav.svelte';
	import OffersBanner from './components/OffersBanner.svelte';
	import ProductRibbon from './components/ProductRibbon.svelte';
	import ProductListing from './components/ProductListing.svelte';
	import SubscriptionForm from './components/SubscriptionForm.svelte';
	import ProductSlider from './components/ProductSlider.svelte';
	import ContactRibbon from './components/ContactRibbon.svelte';
	import Footer from './components/Footer.svelte';
</script>

<main>
	<TopNav />
	<UserNav />
	<CategoryNav />
	<AnnouncementsNav />
	<OffersBanner />
	<ProductRibbon />
	<ProductListing title='Best Buys' />
	<SubscriptionForm />
	<ProductSlider />
	<ContactRibbon />
	<Footer />
</main>

<style>

</style>