<template>
  <div class="page">
    <Myheader message="初 壹"></Myheader>
    <div class="content">
      <ul class="list-container">
        <li>
          <a href="/article/582879332e958a005eb464c1">
            <p class="list-title">2016.11 9周减脂计划</p>
            <p class="list-updated">2016-11-13 22:31:15</p>
            <p class="list-abstract">最近两个月陆续拿到了一些 sp offer，也不负众望取得中期答辩不过的头彩，稀里糊涂的度过了九月十月，身体力量虽然小幅提高，但频率已经降到两天一练甚至两天都不能一练的境况，得过且过的现象简直抓瞎。</p>
          </a>
        </li>
      </ul>
    </div>

  </div>
</template>

<script>
import Myheader from 'components/Header'

export default {
  components: {
    Myheader
  }
}
</script>

<style>
  .list-container{
     a{
        text-decoration: none;
     }

     .list-title{
        font-size: 2rem;
        color: #404040;
     }

     .list-updated{
        font-size: 1.1rem;
        color: #8b8b8b;
     }

     .list-abstract{
        font-size: 1rem;
        color: #919191;
     }

     p{
        margin: 0.5em 0;
     }
  }
</style>
