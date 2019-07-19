<templat>
    <svg class="g-icon">
        <use :xlink:href="'#i-${name}'"></use>
    </svg>
</templat>
<script>
export  default {
    props: ['name']
}
</script>
<style>
    .icon{width: 1em; height: 1em;}
</style>
