var html = require('yo-yo')

var Nav = require('./navbar')

var index = html`
  ${Nav}
  <div>hello world</div>
`

//

const htmlString = index.toHTML()
fs.writeFileSync('index.html', htmlString)


<a href=""
<!-- <img src="cards/principles_Page_02.jpg" width="2481" height="1754" alt="Contents" usemap="#planetmap">
    <map name="planetmap">
    <area shape="rect" coords="99,276,720,322" href="cards/principles_Page_03.jpg" alt="Breastfeeding Importance - Baby 01A">
    <area shape="circle" coords="90,58,3" href="mercur.htm" alt="Mercury">
    <area shape="circle" coords="124,58,8" href="venus.htm" alt="Venus">
    </map> -->