<script>
    import PageHeader from "../lib/PageHeader.svelte";
    import Navigation from "../lib/Navigation.svelte";
    import PageFooter from "../lib/PageFooter.svelte";
    import Analytics from "../lib/analytics.svelte";
    import Meta from "../lib/meta.svelte";
    export let PageHeaderInfo;

</script>

<PageHeader {PageHeaderInfo}/>
<Navigation/>
<Meta/>
<Analytics/>
<slot></slot>
<PageFooter/>