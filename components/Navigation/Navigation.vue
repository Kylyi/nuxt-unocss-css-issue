<template>
  <header bg="white dark:dark" >
    <div class="navigation">
      <nav flex="~ 1 gap-x-2 gap-y-1 wrap" min-h="11">
          <div class="inner">
            Whatever...
          </div>
      </nav>

      <slot name="after" />
    </div>
  </header>
</template>

<style lang="scss" scoped>
header {
  --apply: fixed top-0 left-0 right-0;
}

.navigation {
  --apply: w-full flex flex-gap-2 p-x-1 min-h-13 lg:container m-x-auto;
}

.inner {
  display: flex;
  flex-grow: 1;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
  min-height: 44px;
  margin-block: 0.25rem;
}
</style>
