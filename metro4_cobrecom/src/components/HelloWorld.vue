<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <div class="container-fluid">
    <div class="grid-style">
      <div class="row">
        <div class="cell-md-3">
          <div>3</div>
        </div>
        <div class="cell-md-3">
          <div>6</div>
        </div>
        <div class="cell-md-3">
          <div>9</div>
        </div>
        <div class="cell-md-3">
          <div>12</div>
        </div>
      </div>
      <div class="row">
        <div class="cell-md-3">
          <div>1</div>
        </div>
        <div class="cell-md-3">
          <div>2</div>
        </div>
        <div class="cell-md-3">
          <div>3</div>
        </div>
        <div class="cell-md-3">
          <div>4</div>
        </div>
      </div>
      <div class="row">
        <div class="cell-md-3">
          <div>1</div>
        </div>
        <div class="cell-md-3">
          <div>2</div>
        </div>
        <div class="cell-md-3">
          <div>3</div>
        </div>
        <div class="cell-md-3">
          <div>4</div>
        </div>
      </div>
    </div>
  </div>

  <!--
  <div class="container-fluid start-screen h-100">
    <div class="tiles-area clear">
      <div class="tiles-grid tiles-group size-7 fg-white">
        <div data-role="tile" data-size="wide" class="bg-cyan fg-white selected">
          <span class="mif-power icon"></span>
          <span class="branding-bar">INÍCIO</span>
        </div>
        <div data-role="tile" data-size="wide" class="bg-cyan fg-white">
          <span class="mif-shrink icon"></span>
          <span class="branding-bar">CARGA</span>
        </div>
        <div data-role="tile" data-size="wide" class="bg-cyan fg-white">
          <span class="mif-history icon"></span>
          <span class="branding-bar">REPOSIÇÃO</span>
        </div>
        <div data-role="tile" class="bg-cyan fg-white">
          <span class="mif-backspace icon"></span>
          <span class="branding-bar">DEVOLUÇÃO</span>
        </div>
        <div data-role="tile" data-size="wide" class="bg-cyan fg-white">
          <span class="mif-list icon"></span>
          <span class="branding-bar">REPORTE</span>
        </div>
        <div data-role="tile" class="bg-cyan fg-white">
          <span class="mif-move-down icon"></span>
          <span class="branding-bar">DESCARGA</span>
        </div>
        <div data-role="tile" data-size="wide" class="bg-cyan fg-white">
          <span class="mif-sort-asc icon"></span>
          <span class="branding-bar">RECLASSIFICAÇÃO</span>
        </div>
        <div data-role="tile" data-size="wide" class="bg-cyan fg-white">
          <span class="mif-printer icon"></span>
          <span class="branding-bar">REIMPRESSÃO</span>
        </div>
        <div data-role="tile" class="bg-cyan fg-white">
          <span class="mif-clipboard icon"></span>
          <span class="branding-bar">BAIXA</span>
        </div>
        <div data-role="tile" data-size="wide" class="bg-cyan fg-white">
          <span class="mif-equalizer icon"></span>
          <span class="branding-bar">PROGRAMAÇÃO</span>
        </div>
        <div data-role="tile" data-size="wide" class="bg-cyan fg-white">
          <span class="mif-cross icon"></span>
          <span class="branding-bar">INTERRUPÇÃO</span>
        </div>
        <div data-role="tile" data-size="wide" class="bg-cyan fg-white">
          <span class="mif-infinite icon"></span>
          <span class="branding-bar">MOVIMENTAÇÃO</span>
        </div>
      </div>
    </div>
  </div>
-->
</template>

<style scoped>
div {
  border: 2px solid red;
}

h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {

  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
