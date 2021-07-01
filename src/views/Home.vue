<template>
  <div class="api-list-box">
    <div class="api-list__box-icon">
      <svg viewBox="0 0 1024 1024">
        <path d="M1004.470857 8.265143a45.860571 45.860571 0 0 0-47.177143-3.145143L24.722286 487.716571A45.787429 45.787429 0 0 0 25.088 569.051429l226.011429 114.102857a45.787429 45.787429 0 0 0 41.252571-81.700572L146.212571 527.798857l655.506286-339.236571c-89.892571 108.982857-222.134857 268.580571-292.425143 349.622857-106.422857 122.660571-120.758857 221.476571-120.758857 301.860571v138.24a45.714286 45.714286 0 1 0 91.428572 0v-138.24c0-62.171429 7.606857-137.289143 98.377142-241.956571 82.651429-95.305143 249.490286-297.325714 334.701715-400.822857l-85.357715 674.377143-202.825142-102.326858a45.787429 45.787429 0 0 0-41.179429 81.700572l260.608 131.437714a46.006857 46.006857 0 0 0 42.057143-0.438857 45.714286 45.714286 0 0 0 23.917714-34.596571l113.371429-896a45.641143 45.641143 0 0 0-19.163429-43.154286z" fill="#17B3A3" p-id="4366"></path>
      </svg>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class ApiList extends Vue {

}
</script>
<style lang="scss">

.api-list-box {
  position: fixed;
  bottom: 1px;
  right: 1px;
  width: 4px;
  height: 4px;
  opacity: .9;
  background: #fff;
  overflow: hidden;
  padding: 1px;
  z-index: 2000;
  border-radius: 100%;
  transition-property: width, height,border-radius,opacity;
  transition-duration: 300ms;
  transition-timing-function: linear;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
</style>
