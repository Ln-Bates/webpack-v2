<template>
    <div class="loading-content">

        <!--<img class="loader" src="https://web.langlive.com/html/static/img/loading.gif?v=1512">-->

        <div class="loader loader--style1" title="0">
            <svg version="1.1" id="loader-1" x="0px" y="0px"
   width="1.5rem" height="1.5rem" viewBox="0 0 40 40" enable-background="new 0 0 40 40" xml:space="preserve">
  <path opacity="0.2" fill="#000" d="M20.201,5.169c-8.254,0-14.946,6.692-14.946,14.946c0,8.255,6.692,14.946,14.946,14.946
    s14.946-6.691,14.946-14.946C35.146,11.861,28.455,5.169,20.201,5.169z M20.201,31.749c-6.425,0-11.634-5.208-11.634-11.634
    c0-6.425,5.209-11.634,11.634-11.634c6.425,0,11.633,5.209,11.633,11.634C31.834,26.541,26.626,31.749,20.201,31.749z"/>
  <path fill="#000" d="M26.013,10.047l1.654-2.866c-2.198-1.272-4.743-2.012-7.466-2.012h0v3.312h0
    C22.32,8.481,24.301,9.057,26.013,10.047z">
    <animateTransform attributeType="xml"
      attributeName="transform"
      type="rotate"
      from="0 20 20"
      to="360 20 20"
      dur="0.5s"
      repeatCount="indefinite"/>
    </path>
  </svg>
        </div>


    </div>

</template>

<script>
    export default {
        name: "loading",
    }
</script>

<style scoped>
    .loading-content {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-color: rgba(0, 0, 0, 0.2);
        text-align: center;
        z-index: 1111111;
    }

    .loading-content .loader {
        margin: 65% auto 0;
        width: 1.5rem;
    }

    .loading-content svg {
        overflow: hidden;
    }

    .loading-content path {
        fill: rgb(18, 150, 219);
    }


</style>
