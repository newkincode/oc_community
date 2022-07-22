<script>
    import Bar from '../lib/Bar.svelte'
</script>

<svelte:head><title>관리자 리스트</title></svelte:head>
<Bar />

<pre>
    메시지 관리자:
    Blue Lawliet
    Klumg

    홍보 관리자:
    Blue Lawliet

    어드 : OTTO
</pre>


<style>
    @font-face {
    font-family: 'IM_Hyemin-Bold';
    src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2106@1.1/IM_Hyemin-Bold.woff2') format('woff');
    font-weight: normal;
    font-style: normal;
}
pre{
    font-family: 'IM_Hyemin-Bold';
    position: relative;
    top: 100px;
    font-size: 20px;
}

</style>