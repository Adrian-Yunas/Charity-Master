<script>
  import CharityList from "../components/CharityList.svelte";
  import Header from "../components/header.svelte";
  import Welcome from "../components/Welcome.svelte";
  import Promo from "../components/promo.svelte";
  import Footer from "../components/footer.svelte";
  import { charities } from "../data/charities.js";

  let title = "Charity";
</script>

<Header />
<Welcome />
<CharityList {charities} />
<Promo />
<Footer />
