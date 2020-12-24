<template lang="pug">
.newscontainer
  .rectangleur
  .bigtitle {{bigtext}}
  .bigtitle2 {{big2text}}
  .imgcool
  .onetitle {{onetext}}
  .twotitle {{twotext}}
  .threetitle {{threetext}}
  .fourtitle {{fourtext}}
  .fivetitle {{fivetext}}
  .line1dv
  .line1dh
  .linel
  .liner1
  .imgbboom
  .line2l
  .line2r
  .line2r2
  .line2d
  .rectangleur2
    .recp2title {{recp2text}}
  .p2title {{p2text}}
  .lutitle {{lutext}}
  .ldtitle {{ldtext}}
  .l1title {{l1text}}
  .l2title {{l2text}}
  .l3title {{l3text}}
  .l4title {{l4text}}
  .l5title {{l5text}}
  .p2title {{p2text}}
  .black
  .p3title {{p3text}}
  .p3cu {{p3cutext}}
  .p3cd {{p3cdtext}}
  .p3cr {{p3crtext}}
  .imgu
  .imgdl
  .imgdr
  .p3liner
  .p3linel
  .p3lineur
  .p3lineul
  .p3lined
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default{
  name: 'Home',
  component: {
    HelloWorld
  },

  data() {
    return{
      bigtext: '清華大學',
      big2text:'藝術學院',
      smalltext: 'N',
      ttext:'T',
      htext:'H',
      utext:'U',
      lutext: '學士班特色',
      ldtext: '核心能力',
      l1text: '清華是國際頂尖科技大學，加上合校後的藝術學院，具備發展「科技藝術」的卓越條件。我們號召臺灣年輕一代的科技藝術學者專家，我們規劃有科技藝術跨域特別課程，並與業界合作推出創意跨域專題。你，不需猶豫，歡迎你的加入！',
      l2text: '社會關懷與品格實踐能力 美感認知與經典欣賞能力 自然感知與創新發想能力 邏輯思辨與語文溝通能力 國際觀點與在地行動能力 資訊掌握與科技應用能力',
      l3text: '清華大學2018年成立藝術學院〝科技藝術〞跨域「學士班」。「科技藝術（TechArt）」是當代藝術的新形式創作也是國際藝術發展的重要趨勢，包含虛擬藝術、互動藝術、電腦動畫、電腦音樂、聲音藝術、科技性表演藝術、混合藝術、網路社群、創客藝術、仿生藝術、生物藝術、人工生命…等。在當代數位美學與數位藝術的基礎下，我們結合創新科技，如各種互動感測技術、虛擬實境、物聯網、人工智慧、大數據分析、基因工程…，把「科技」與「藝術」結合視為「未來文化學」，培養前瞻性、跨域研究與創作人才。',
      l4text: '因應未來產業的發展趨勢，創新科技與當代藝術結合之創作如雨後春筍。清華大學的是國內科學與科技的頂尖學府，對藝術學院發展「科技藝術」具有得天獨厚的優勢。本班師資除來自清華校內藝術學院、',
      l5text: '電資學院、工學院、生命科學院、人文社會等跨域教師外，我們也將聘進一群來自美國、歐洲與日本跨國與跨域的專業教師。也廣邀在臺灣在科技藝術創作領域最頂尖的業界團隊與藝術家加入我們的教學團隊，讓同學得到專業與多元的指導，並在共享學習、共享創意的環境裡，開創未來的產業，盡情發揮自己的潛能。',
      p3text: '| 院學士班消息 |',
      p2text:'Home',
      p3cutext: '獎項相關',
      p3cdtext: '展覽相關',
      p3crtext: '講座相關',
      onetext:'招生',
      twotext:'學士班',
      threetext:'師資',
      fourtext:'科藝賞析',
      fivetext:'聯絡',
      
    }
  }
}

</script>

<style >

.newscontainer {
position: relative;
width: 1920px;
height: 3072px;
overflow-y: scroll;
background: #FFFFFF;
}
  .bigtitle {
  position: absolute;
  width: 821px;
  height: 190px;
  left: 1162px;
  top: 97px;
  font-family: Zilla Slab;
  font-style: normal;
  font-weight: normal;
  font-size: 60px;
  line-height: 72px;
  letter-spacing: 0.6em;
  color: #FFFFFF;
  }
  .bigtitle2{
    position: absolute;
    width: 472px;
    height: 106px;
    left: 1512px;
    top: 190px;
    font-family: Zilla Slab;
    font-style: normal;
    font-weight: normal;
    font-size: 60px;
    line-height: 72px;
    letter-spacing: 0.6em;
    color: #FFFFFF;
  }

  .imgcool {
  position: absolute;
  width: 1314px;
  height: 774px;
  left: -318px;
  top: -100px;
  background-image: url('https://img.onl/5O3MPW');
  background-size: cover;
  }

  .rectangleur {
  position: absolute;
  width: 1040px;
  height: 674px;
  left: 928px;
  top: 0px;
  background: #000000;
  }
  .line1dv {
    position: absolut;
    width: 126px;
    height: 0px;
    left: 1802px;
    top: 633px;
    border: 2px solid #FFFFFF;
    transform: rotate(-90deg);
  }
  .line1dh {
    position: absolute;
    width: 381px;
    height: 0px;
    left: 1479px;
    top: 633px;
    border: 2px solid #FFFFFF;
  }
  .imgbboom {
    position: absolute;
    width: 1939px;
    height: 400px;
    left: 0px;
    top: 674px;
    background-image: url('https://img.onl/vEdFik');
    background-size: cover;
  }
  .onetitle{
    position: absolute;
    width: 61px;
    height: 32px;
    left: 250px;
    top: 610px;
    font-family: Tuffy;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 30px;
    letter-spacing: 0.5em;
    color: #FFFFFF;
  }
  .twotitle{
    position: absolute;
    width: 110px;
    height: 32px;
    left: 400px;
    top: 610px;
    font-family: Tuffy;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 30px;
    letter-spacing: 0.5em;
    color: #FFFFFF;
  }
  .threetitle {
    position: absolute;
    width: 110px;
    height: 32px;
    left: 550px;
    top: 610px;
    font-family: Tuffy;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 30px;
    letter-spacing: 0.5em;
    color: #FFFFFF;
  }
  .fourtitle {
    position: absolute;
    width: 134px;
    height: 32px;
    left: 700px;
    top: 610px;
    font-family: Tuffy;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 30px;
    letter-spacing: 0.5em;
    color: #FFFFFF;
  }
  .fivetitle{
    position: absolute;
    width: 110px;
    height: 32px;
    left: 850px;
    top: 610px;
    font-family: Tuffy;
    font-style: normal;
    font-weight: bold;
    font-size: 20px;
    line-height: 30px;
    letter-spacing: 0.5em;
    color: #FFFFFF;
  }
  .p2title{
    position: absolute;
    width: 96px;
    height: 31px;
    left: 1724px;
    top: 1489px;
    font-family: Tuffy;
    font-style: normal;
    font-weight: bold;
    font-size: 26px;
    line-height: 39px;
    letter-spacing: 0.4em;
    color: #FFFFFF;
  }

  .rectangleur2 {
  position: absolute;
  width: 204px;
  height: 115px;
  left: 1670px;
  top: 1447px;
  background: #000000;
  }
  .recp2title {
  position: absolute;
  width: 96px;
  height: 31px;
  left: 1724px;
  top: 1489px;
  font-family: Tuffy;
  font-style: normal;
  font-weight: bold;
  font-size: 26px;
  line-height: 39px;
  letter-spacing: 0.4em;
  color: #FFFFFF;
  }
  .lutitle {
  position: absolute;
  width: 178px;
  height: 32px;
  left: 314px;
  top: 1150px;
  font-family: Tuffy;
  font-style: normal;
  font-weight: bold;
  font-size: 22px;
  line-height: 33px;
  letter-spacing: 0.4em;
  color: #1D938C;
  }
  .ldtitle {
  position: absolute;
  width: 178px;
  height: 47px;
  left: 333px;
  top: 1536px;
  font-family: Tuffy;
  font-style: normal;
  font-weight: bold;
  font-size: 22px;
  line-height: 33px;
  letter-spacing: 0.4em;
  color: #052B28;
  }
  .l1title {
  position: absolute;
  width: 384px;
  height: 284px;
  left: 234px;
  top: 1226px;
  font-family: Tuffy;
  font-style: normal;
  font-weight: bold;
  font-size: 20px;
  line-height: 30px;
  letter-spacing: 0.4em;
  color: #888888;
  }
  .l2title {
  position: absolute;
  width: 358px;
  height: 262px;
  left: 238px;
  top: 1615px;
  font-family: Tuffy;
  font-style: normal;
  font-weight: bold;
  font-size: 20px;
  line-height: 30px;
  letter-spacing: 0.4em;
  color: #888888;
  }
  .l3title {
  position: absolute;
  width: 852px;
  height: 282px;
  left: 860px;
  top: 1159px;
  font-family: Tuffy;
  font-style: normal;
  font-weight: bold;
  font-size: 20px;
  line-height: 30px;
  letter-spacing: 0.4em;
  color: #888888;
  }
  .l4title {
  position: absolute;
  width: 734px;
  height: 126px;
  left: 860px;
  top: 1473px;
  font-family: Tuffy;
  font-style: normal;
  font-weight: bold;
  font-size: 20px;
  line-height: 30px;
  letter-spacing: 0.4em;
  color: #888888;
  }
  .l5title {
  position: absolute;
  width: 833px;
  height: 244px;
  left: 860px;
  top: 1697px;
  font-family: Tuffy;
  font-style: normal;
  font-weight: bold;
  font-size: 20px;
  line-height: 30px;
  letter-spacing: 0.4em;
  color: #888888;
  }

  .black {
    position: relative;
    width: 1920px;
    height: 1024px;
    top:2070px;
    overflow-y: scroll;
    background: #000000;
  }


  .p3title {
  position: absolute;
  width: 480px;
  height: 92px;
  left: 600px;
  top: 2121px;
  font-family: Tuffy;
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 36px;
  letter-spacing: 0.5em;
  color: #FFFFFF;
  }
  .p3cu {
  position: absolute;
  width: 166px;
  height: 42px;
  left: 286px;
  top: 2229px;
  font-family: Tuffy;
  font-style: normal;
  font-weight: bold;
  font-size: 26px;
  line-height: 39px;
  letter-spacing: 0.5em;
  color: #FFFFFF;
  }
  .p3cd {
  position: absolute;
  width: 208px;
  height: 58px;
  left: 286px;
  top: 2622px;
  font-family: Tuffy;
  font-style: normal;
  font-weight: bold;
  font-size: 26px;
  line-height: 39px;
  letter-spacing: 0.5em;
  color: #FFFFFF;
  }
  .p3cr {
  position: absolute;
  width: 191px;
  height: 40px;
  left: 1095px;
  top: 2624px;
  font-family: Tuffy;
  font-style: normal;
  font-weight: bold;
  font-size: 26px;
  line-height: 39px;
  letter-spacing: 0.5em;
  color: #FFFFFF;
  }
  .imgu {
    position: absolute;
    width: 1130px;
    height: 253px;
    left: 286px;
    top: 2311px;
    background: url('https://img.onl/sa9rQC');
    background-size: cover;
  }
  .imgdl {
    position: absolute;
    width: 614px;
    height: 387px;
    left: 286px;
    top: 2693px;
    background: url('https://img.onl/5OKY6G');
    background-size: cover;
  }
  .imgdr {
    position: absolute;
    width: 593px;
    height: 382px;
    left: 1027px;
    top: 2699px;
    background: url('https://img.onl/fkwzoF');
    background-size: cover;
  }
  .p3liner {
  position: absolute;
  width: 1009px;
  height: 0px;
  left: 1840px;
  top: 3158px;
  border: 2px solid #FFFFFF;
  transform: rotate(-90deg);
  }

  .p3lined {
  position: absolute;
  width: 1779px;
  height: 0px;
  left: 1840px;
  top: 3157.97px;
  border: 2px solid #FFFFFF;
  transform: rotate(-179.87deg);
  }

</style>