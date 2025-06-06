<div class="product-container">

<div class="product-header">
  <h1 class="product-title">全新磷酸铁锂A品电芯</h1>
  <p class="product-tagline">值得信赖的选择</p>
</div>

<div class="product-gallery">
  <div class="main-image">
    <img id="main-product-image" src="/images/wrapper-img.png" alt="磷酸铁锂电池主图">
  </div>
  
  <div class="thumbnails">
    <div class="thumbnail" onclick="changeMainImage('/images/wrapper-img.png', '整体外观')">
      <img src="/images/wrapper-img.png" alt="整体外观">
    </div>
    <div class="thumbnail" onclick="changeMainImage('/images/battery-detail.jpg', '电池结构')">
      <img src="/images/wrapper-img.jpg" alt="电池结构">
    </div>
    <div class="thumbnail" onclick="changeMainImage('/images/feature-bg.jpg', '应用场景')">
      <img src="/images/feature-bg.jpg" alt="应用场景">
    </div>
  </div>
</div>

<script>
function changeMainImage(src, alt) {
  document.getElementById('main-product-image').src = src;
  document.getElementById('main-product-image').alt = alt;
  
  // 可选：添加活动状态的样式
  const thumbnails = document.querySelectorAll('.thumbnail');
  thumbnails.forEach(thumb => {
    thumb.classList.remove('active');
  });
  event.currentTarget.classList.add('active');
}
</script>

<style>
/* 添加活动状态样式 */
.thumbnail.active {
  border: 2px solid #3498db;
  box-shadow: 0 0 10px rgba(52, 152, 219, 0.5);
}

.thumbnail {
  cursor: pointer;
  transition: all 0.3s ease;
  border: 2px solid transparent;
}

.thumbnail:hover {
  transform: scale(1.05);
}
</style>


<div class="product-specs">
  <h2>产品技术规格</h2>
  <table>
    <tr>
      <th>技术参数</th>
      <th>规格详情</th>
    </tr>
    <tr>
      <td>电池类型</td>
      <td>磷酸铁锂（LiFePO₄）动力电池</td>
    </tr>
    <tr>
      <td>标称电压</td>
      <td>12V/24V/48V（可定制）</td>
    </tr>
    <tr>
      <td>额定容量</td>
      <td>50Ah-200Ah（支持组串扩容）</td>
    </tr>
    <tr>
      <td>循环寿命</td>
      <td>≥2500次（80% DoD，国标测试条件）</td>
    </tr>
    <tr>
      <td>设计寿命</td>
      <td>8-10年（25℃标准环境）</td>
    </tr>
    <tr>
      <td>工作温度</td>
      <td>-20℃~55℃（支持低温加热选配）</td>
    </tr>
    <tr>
      <td>充电效率</td>
      <td>≥95%（0.5C充电速率）</td>
    </tr>
    <tr>
      <td>安装方式</td>
      <td>卧式安装（IP65防护等级）</td>
    </tr>
    <tr>
      <td>安全认证</td>
      <td>GB/T、CE、UN38.3认证</td>
    </tr>
  </table>
</div>

<div class="product-highlights">
  <h2>产品核心优势</h2>
  
  <div class="highlight">
    <h3>⚡ 安全</h3>
    <p>采用磷酸铁锂化学体系，热失控温度高达500℃，通过针刺/挤压等极端安全测试，彻底解决三元电池起火风险</p>
  </div>
  
  <div class="highlight">
    <h3>🔄 超长寿命</h3>
    <p>2500次循环后容量保持率＞80%，日历寿命达10年，较铅酸电池使用成本降低60%</p>
  </div>
  
  <div class="highlight">
    <h3>❄️ 低温战神</h3>
    <p>-20℃低温环境下仍保持85%容量输出，可选配智能预热系统，攻克北方冬季续航痛点</p>
  </div>
  
  <div class="highlight">
    <h3>🏋️ 高能密度</h3>
    <p>体积能量密度达300Wh/L，同等容量下比铅酸电池轻40%，有效提升车辆载重能力</p>
  </div>
  
  <div class="highlight">
    <h3>🔧 即装即用</h3>
    <p>标准化接口设计，兼容市面主流三四轮车电气系统，支持铅酸电池原位替换</p>
  </div>
</div>

<div class="testimonials">
  <h2>用户反馈</h2>
  
  <div class="review">
    <div class="rating">★★★★★</div>
    <p>"换了这套电池后，我的快递三轮车续航从80公里提升到130公里，每天少充一次电，半年就省出了电池钱！充电站老板都说我最近去得少了。"</p>
    <div class="reviewer">- 王强，物流公司配送员 | 使用10个月</div>
  </div>
  
  <div class="review">
    <div class="rating">★★★★★</div>
    <p>"在黑龙江用了两个冬天，零下25度照样能启动，以前铅酸电池到这个温度只能跑三分之一路程，现在至少能保证70%续航，终于不用推车了。"</p>
    <div class="reviewer">- 赵雪峰，哈尔滨菜贩 | 使用2个冬季</div>
  </div>
  
  <div class="review">
    <div class="rating">★★★★☆</div>
    <p>"电池管理系统很精准，手机能实时看到剩余电量百分比，再也不用像以前那样靠电压猜电量了。就是快充时发热稍微明显，建议配套散热更好的充电器。"</p>
    <div class="reviewer">- 李师傅，电动车维修店主 | 测试15组电池</div>
  </div>

<div class="faq">
  <h2>常见问题解答</h2>
  
  <details>
    <summary>订单的生产周期是多久？</summary>
    <p>常规订单在付款确认后3-5个工作日内发货，批量订单可能需要7-10天的生产时间。</p>
  </details>
  
  <details>
    <summary>接受小批量订单吗？</summary>
    <p>支持最小10件的样品订单，方便您验证产品质量。具体需求欢迎通过邮件或电话与我们沟通。</p>
  </details>
  
  <details>
    <summary>支持哪些付款方式？</summary>
    <p>我们接受电汇(T/T)、支付宝、PayPal以及阿里巴巴担保交易，保障资金安全。</p>
  </details>
  
  <details>
    <summary>如何处理质量问题？</summary>
    <p>提供1年质保服务，只需提供问题产品照片/视频，我们将立即安排换货或退款。</p>
  </details>
  
  <details>
    <summary>发货到哪些国家？</summary>
    <p>目前通过DHL/联邦快递覆盖欧美、东南亚地区，具体运费和时效欢迎咨询。</p>
  </details>
  
  <details>
    <summary>有进出口资质吗？</summary>
    <p>我们拥有完整的进出口经营权，可提供原产地证、质检报告等全套清关文件。</p>
  </details>
  
  <details>
    <summary>如何获取更多产品信息？</summary>
    <p>欢迎随时联系我们的外贸团队：<br>
    电话：+86 123 4567 8910<br>
    邮箱：export@yourcompany.com<br>
    工作日9:00-18:00在线响应</p>
  </details>
</div>

</div>

<style>
.product-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  color: #333;
}

.product-header {
  text-align: center;
  margin-bottom: 40px;
}

.product-title {
  font-size: 2.5rem;
  color: #2c3e50;
  margin-bottom: 10px;
}

.product-tagline {
  font-size: 1.2rem;
  color: #7f8c8d;
}

.product-gallery {
  display: flex;
  flex-direction: column;
  gap: 20px;
  margin-bottom: 40px;
}

.main-image img {
  width: 100%;
  border-radius: 10px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

.thumbnails {
  display: flex;
  gap: 15px;
  justify-content: center;
}

.thumbnail img {
  width: 100%;
  max-width: 120px;
  border-radius: 8px;
  transition: transform 0.3s;
  cursor: pointer;
}

.thumbnail img:hover {
  transform: scale(1.05);
}

.product-info {
  display: flex;
  justify-content: center;
  margin-bottom: 50px;
}

.pricing-box {
  background: #f8f9fa;
  border-radius: 12px;
  padding: 25px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
  width: 100%;
  max-width: 350px;
}

.pricing-box h2 {
  font-size: 2.2rem;
  color: #e74c3c;
  margin: 0 0 10px 0;
}

.original-price {
  font-size: 1.2rem;
  color: #95a5a6;
  text-decoration: line-through;
}

.discount {
  background: #e74c3c;
  color: white;
  display: inline-block;
  padding: 5px 10px;
  border-radius: 20px;
  font-weight: bold;
  margin-bottom: 20px;
}

.features {
  margin: 25px 0;
}

.feature {
  display: flex;
  align-items: center;
  margin-bottom: 12px;
  font-size: 1.1rem;
}

.icon {
  background: #2ecc71;
  color: white;
  width: 24px;
  height: 24px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin-right: 10px;
}

.cta-buttons {
  display: flex;
  flex-direction: column;
  gap: 15px;
}

.buy-now, .add-to-cart {
  padding: 15px;
  border: none;
  border-radius: 8px;
  font-size: 1.1rem;
  font-weight: bold;
  cursor: pointer;
  transition: all 0.3s;
}

.buy-now {
  background: #e74c3c;
  color: white;
}

.buy-now:hover {
  background: #c0392b;
}

.add-to-cart {
  background: #3498db;
  color: white;
}

.add-to-cart:hover {
  background: #2980b9;
}

.product-specs {
  margin-bottom: 50px;
}

.product-specs h2, .product-highlights h2, .testimonials h2, .faq h2 {
  text-align: center;
  font-size: 1.8rem;
  color: #2c3e50;
  margin-bottom: 30px;
  padding-bottom: 10px;
  border-bottom: 2px solid #3498db;
  display: inline-block;
}

table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 20px;
}

th, td {
  padding: 15px;
  text-align: left;
  border-bottom: 1px solid #ecf0f1;
}

th {
  background-color: #f8f9fa;
  font-weight: 600;
}

tr:hover {
  background-color: #f5f7fa;
}

.product-highlights {
  margin-bottom: 50px;
}

.highlight {
  background: white;
  border-radius: 10px;
  padding: 20px;
  margin-bottom: 20px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.05);
  transition: transform 0.3s;
  border-left: 4px solid #3498db;
}

.highlight:hover {
  transform: translateY(-5px);
}

.highlight h3 {
  margin-top: 0;
  font-size: 1.4rem;
  color: #2c3e50;
}

.testimonials {
  margin-bottom: 50px;
}

.review {
  background: white;
  border-radius: 10px;
  padding: 25px;
  margin-bottom: 25px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.05);
}

.rating {
  color: #f39c12;
  font-size: 1.4rem;
  margin-bottom: 15px;
}

.reviewer {
  font-style: italic;
  color: #7f8c8d;
  margin-top: 15px;
  text-align: right;
}

.faq details {
  margin-bottom: 15px;
  border: 1px solid #ecf0f1;
  border-radius: 8px;
  padding: 15px;
}

.faq summary {
  font-weight: bold;
  cursor: pointer;
  font-size: 1.1rem;
}

.faq p {
  margin-top: 15px;
  padding-left: 10px;
  color: #34495e;
}

@media (max-width: 768px) {
  .product-gallery {
    flex-direction: column;
  }
  
  .thumbnails {
    flex-wrap: wrap;
  }
  
  .pricing-box {
    max-width: 100%;
  }
}
</style>