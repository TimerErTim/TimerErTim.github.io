<script lang='ts'>
    import logo from './github-logo.png'
    import mark from './github-mark.png'

    export let target: string
</script>

<a class='text-blue-600 hover:no-underline content-center' href={target} target='_blank'>
    <img alt='Github' class='inline h-5' src={logo} />
    <img alt='' class='inline h-4' src={mark} />
</a>
