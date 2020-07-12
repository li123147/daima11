<template>
  <div id="my">
    <section class="user-info">
      <img src="http://cn.gravatar.com/avatar/1?s=128&d=identicon" alt="" class="avatar">
      <h3>小阿鱼</h3>
    </section>
    <section>
      <div class="item">
        <div class="date">
          <span class="day">20</span>
          <span class="month">2月</span>
          <span class="year">2019</span>
        </div>
        <h3>“挨饿德荒野大揭秘”</h3>
        <p>《决胜荒野之华夏秘境》是一个真实的野外生存竞赛节目模式，节目场景建立在世界上一些最致命的环境中进行生存挑战PK。在每一集中，德爷都面临着一个完全不同的，但又同样熟悉生存挑战的对手。在一场充满危险的旅程中，他们将竞争谁是第一个达到预定目的地的人。极端的荒野自然环境是本系列节目真实性的关键，我们的冒险家将带领观众走到生存的极限边缘。本系列节目的最大看点是当德爷和他的对手经过重重荒野挑战冒险，出生入死已经达到他们个人的极限后，他们还需要更进一步挑战成为第一个达到终点的人...</p>
        <div class="actions">
          <router-link to="/edit">编辑</router-link>
          <a href="#">删除</a>
        </div>
      </div>
    </section>
  </div>
</template>

<script src="./template.js"></script>

<style src="./template.less" lang="less"></style>
