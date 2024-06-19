---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
page_header: Home
---
<style>
    .dark-mode * {
        background-color: black;
        color: white;
    }
</style>

<div>
    <button onclick="darkmode()">Dark Mode</button>
</div>

<script>
    function darkmode() {
        document.body.classList.toggle("dark-mode");
    }
</script>
