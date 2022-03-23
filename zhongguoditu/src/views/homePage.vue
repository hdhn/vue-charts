<template>
  <div>
      <header>
          <h1>
              大数据可视化
          </h1>
      </header>
      <!-- 大容器 -->
      <section class="container">
          <!-- 左容器 -->
          <section class="itemLeft">
              <ItemPage>

              </ItemPage>
          </section>
          <!-- 中容器 -->
          <section class="itemCenter"></section>
          <!-- 右容器 -->
          <section class="itemRight">
              <ItemPage>

              </ItemPage>
          </section>
      </section>
  </div>
</template>

<script>
import itemPage from "@/components/itemPage.vue"
import ItemPage from "@/components/itemPage.vue"
import ItemPage from "@/components/itemPage.vue"
export default {
    com
}
</script>

<style lang ="less">
header{
    height: 80px;
    width :100%;
    background-color: rgb(12, 12, 180); 
    /* 标题的文字样式 */
    h1{
        font-size: 0.375rem;
        color:#fff;
        text-align: center;
        line-height: 1rem;
    }
}
/* h1{
    font-size: 0.875rem;
    color: #fff;
    text-align: center;
    line-height: 1rem;
} */
/* 大容器的样式 */
.container{
    /* 最大最小的宽度 */
    min-width: 1200px;
    max-width: 2048px;
    margin: 0 auto;
    padding: 10px 10px 0;
    height: 500px;
    background-color: gray;
    display: flex;
    .itemLeft,.itemRight{
        flex: 3;
    }
    .itemCenter{
        flex: 5;
    }
}
 /* div{
     font-size: .625rem;
     color: rgb(230, 219, 219);
 } */
 
</style>