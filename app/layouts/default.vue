<template>
  <main h-full>
    <div flex flex-col gap-4 px-4 pb-4 pt-4>
      <div flex items-center gap-2 text-4xl>
        <img src="/logo.svg" alt="Qrs" size-1em>
        <h1>
          Qrs
        </h1>
      </div>
      <div h-full flex gap-8>
        <NuxtLink op70 hover="text-blue" duration-300 transition="all ease-in-out" to="/" active-class="!op100" flex="~ items-center gap-1">
          <span i-carbon-upload inline-block />
          Transfer
        </NuxtLink>
        <NuxtLink op70 hover="text-blue" duration-300 transition="all ease-in-out" to="/scan" active-class="!op100" flex="~ items-center gap-1">
          <span i-carbon-download inline-block />
          Receive
        </NuxtLink>
      </div>
    </div>
    <slot />
    <div flex flex-col items-center px-4 py-2>
      <a href="https://github.com/qqrss/qrs" target="_blank" op70 hover="text-blue" duration-300 transition="all ease-in-out" flex="~ items-center gap-1">
        <span i-carbon:logo-github inline-block /><span>GitHub</span>
      </a>
    </div>
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-5638905191417408"
     crossorigin="anonymous"></script>
      <ins class="adsbygoogle"
           style="display:block"
           data-ad-client="ca-pub-5638905191417408"
           data-ad-slot="3440653847"
           data-ad-format="auto"
           data-full-width-responsive="true"></ins>
      <script>
           (adsbygoogle = window.adsbygoogle || []).push({});
      </script>
  </main>
</template>
