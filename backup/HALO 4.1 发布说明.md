<h1>HALO 4.1 发布说明</h1>

<p><strong>软件更新 | 2025 年 2 月</strong><br>仅供研究使用</p>

<hr>

<h2>HALO v4.1</h2>

<h3>新功能</h3>
<ul>
  <li><strong>图像制作器（Figure Maker）：保存正在进行的图像以便稍后编辑</strong>
    <ul>
      <li>遵循 HALO Link 的研究级权限</li>
      <li>重新设计的布局，与新的 HALO Link 图像制作器保持一致</li>
    </ul>
  </li>
  <li><strong>图像视图设置应用</strong>
    <ul>
      <li>每个通道单独应用自动适配视图设置计算</li>
      <li>批量应用视图设置，无需导出/导入</li>
    </ul>
  </li>
  <li><strong>图像视图设置直方图</strong>
    <ul>
      <li>可比较多个已打开图像的直方图</li>
      <li>显示相对强度值</li>
      <li>显示真实伽马值和伽马曲线</li>
      <li>可使用对数视图</li>
    </ul>
  </li>
  <li><strong>高通量图像（highplexed images）表型设置优化</strong>
    <ul>
      <li>新的设置选择网格</li>
      <li>一次性为所有通道设定逻辑</li>
      <li>实时查看每个表型的调优标记</li>
      <li>分析标签页中显示表型预览列表</li>
      <li>支持将表型逻辑导出为 <code>.csv</code></li>
    </ul>
  </li>
  <li><strong>HALO 图像写入器生成 OME.TIFF 图像</strong>
    <ul>
      <li>拼接组件 <code>.qptiff</code></li>
      <li>融合的序列染色</li>
      <li>导出全分辨率图像</li>
      <li>静态标记图像</li>
    </ul>
  </li>
  <li><strong>更新的用户通知</strong>
    <ul>
      <li>所有通知显示在 HALO 右下角</li>
      <li>支持同时显示多个提醒</li>
      <li>点击即可关闭通知</li>
      <li>可选记录错误消息以便故障排查</li>
    </ul>
  </li>
</ul>

<hr>

<h2>分析模块更新</h2>
<ul>
  <li><strong>高维分析模块（High Dimensional Analysis） - 新增</strong>
    <ul>
      <li>无监督聚类</li>
      <li>降维图</li>
      <li>在图像、对象数据和图表之间保持交互性</li>
    </ul>
  </li>
  <li><strong>Highplex FL 模块 v5.0</strong>
    <ul>
      <li>支持阈值辅助（Threshold Assist）工作流</li>
      <li>支持上文所述的高通量表型设置优化</li>
    </ul>
  </li>
</ul>

<hr>

<h2>HALO AI</h2>
<ul>
  <li><strong>AI 标注工具改进</strong>
    <ul>
      <li>改进的 UI/UX</li>
      <li>支持多图像</li>
      <li>原生支持 FL 图像</li>
    </ul>
  </li>
  <li><strong>分类器流水线</strong>
    <ul>
      <li>标记下拉菜单显示分类器名称</li>
      <li>第一个标记叠加层显示最终步骤结果</li>
    </ul>
  </li>
  <li><strong>AI 应用（AI Apps）支持改进</strong>
    <ul>
      <li>简化批量分析</li>
      <li>在 HALO 界面中提供 AI Apps 用户指南</li>
    </ul>
  </li>
  <li><strong>额外的批量工作流</strong>
    <ul>
      <li>批量将分类器训练区域移动到标注标签页</li>
      <li>批量删除验证标注集</li>
    </ul>
  </li>
  <li><strong>支持导出最终定型的分类器</strong></li>
</ul>

<hr>

<h2>已移除的功能</h2>
<ul>
  <li><strong>手动点击计数器</strong> - 已由针状标注工作流替代</li>
  <li><strong>GRPC 服务器</strong> - 已由 GraphQL 服务器取代，成为唯一 API</li>
  <li>自 HALO v4.0 起，不再测试或正式支持与 eSlide Manager 的集成</li>
</ul>

<hr>

<h2>即将移除的功能</h2>
<p>无</p>

<blockquote>
<p>每个 HALO 版本都会新增功能和更新模块。<br>这些改进可能会导致不同版本 HALO 的分析结果略有差异。</p>
</blockquote>

<p>如需更多信息或有任何问题，请联系 <strong>support@indicalab.com</strong></p>

<p>访问 <strong><a href="https://learn.indicalab.com/">Indica Labs 在线学习门户</a></strong> 以了解更多新功能信息。</p><!--##{"timestamp":1744100981}##-->