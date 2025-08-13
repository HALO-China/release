<h1>HALO v4.1.5944.271 Patch 2 优化说明</h1>

<p><strong>软件更新 | 2025 年 7 月</strong><br>仅供研究使用</p>

<hr>

<h2>HALO v4.1.5944.271</h2>

<h3>优化内容</h3>
<ul>
  <li>优化批量分析时的标注加载通知机制。
  <li>优化了在加载已保存的聚类结果（Clusteing result）后再次运行分析的 UMAP 报错。</li>
  <li>优化了 RTT 时发生的 OpenGL 报错，并提升性能。</li>
  <li>优化了空间分析密度热图（Spatial Analysis Density Heatmap）的计算方式，避免在处理超大分析区域（ROA）时一次性计算整个热图导致 HALO 崩溃的问题。</li>
  <li>优化高分辨率大尺寸图像，解决在高倍缩放（约 20x–40x）浏览图像时，显存（VRAM）快速占满并溢出到系统内存，导致内存持续攀升且无法及时释放的问题。</li>
  <li>将 Threshold Assist 窗口设置为“始终置顶”，避免其在切回 HALO 主窗口时被遮挡。现在，该窗口在使用过程中会始终保持在最前方显示。</li>
  <li>优化 Threshold Assist 直方图的构建方式，现在直方图在不同本地化环境中显示一致，仅在分隔符显示上根据所选本地化进行调整。</li>
  <li>改进 BIF 图像的显示方式，使其与 NDPI 等其他格式一致。</li>
  <li>优化了文件监控（File Monitor）。</li>
  <li>优化了图像导出以及高分辨率图像导出逻辑。</li>
  <li>更新安装程序，优化 MySQL 密码加密，以符合 MySQL 默认安全策略。</li>
  <li>优化视图设置（View Settings）导入与保存逻辑。同时新增了验证机制，方便用户发现并确认设置同步状态。</li>
  <li>提升包含 FL Phenotyper 的分析流 Pipeline 性能。</li>
  <li>优化 TMA 模块缩略图加载逻辑。
  <li>在 Cluster UMAP 中可通过右键菜单切换图例显示，以避免大量 Cluster 图例遮挡图表。</li>
  <li>优化 Wave 2 AI。</li>
  <li>在 OME-TIFF 读取器中增加对报告 16 位但实际为 8 位的 Lunaphore 图像的支持。</li>
  <li>提升重新配置过程的稳定性与可调试性。</li>
  <li>在分析队列窗口新增选项，可关闭作业失败通知，以避免通知在所有已登录 HALO 用户界面上同时弹出。</li>
  <li>优化 Threshold Assist 直方图构建逻辑。</li>
</ul>

<h3>新功能</h3>
<ul>
  <li><strong>暂无</strong></li>
</ul><!--##{"timestamp":1752740981}##-->