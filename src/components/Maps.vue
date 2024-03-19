<template>
  <div class="flex justify-center items-center my-5">
    <h1
      class="font-ImperialScript text-primary xxsm:text-2xl xsm:text-2xl sm:text-4xl md:text-4xl lg:text-5xl xl:text-6xl 2xl:text-7xl"
    >
      Petunjuk Lokasi Acara
    </h1>
  </div>

  <div class="mapouter flex justify-center items-center">
    <div class="gmap_canvas">
      <iframe
        class="gmap_iframe rounded-lg border-solid border-2 border-primary flex justify-center items-center flex-col text-center p-4 xxsm:w-[250px] xsm:w-[290px] sm:w-[380px] md:w-[600px] lg:w-[700px] lg:h-[800px] xl:w-[900px] transition ease-in-out delay-150 bg-white hover:-translate-y-1 hover:scale-110 duration-300 cursor-pointer"
        width="100%"
        frameborder="0"
        scrolling="no"
        marginheight="0"
        marginwidth="0"
        src="https://maps.google.com/maps?width=660&amp;height=380&amp;hl=en&amp;q=-8.095230629901016, 115.10805431374482&amp;t=&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"
      ></iframe>
    </div>
  </div>
</template>
<style>
.mapouter {
  position: relative;
  text-align: right;
  width: 100%;
  height: 380px;
}
.gmap_canvas {
  overflow: hidden;
  background: none !important;
}
.gmap_iframe {
  height: 380px !important;
}
</style>
