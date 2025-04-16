<h2>Accident Analyzer</h2>
<p>A web-based MVP for automated analysis of cause against Accident safety regulations.</p>

<h2>About The Project</h2>
<p>This application provides automated fire safety compliance checking for cause of accident, specifically designed for the. The system processes uploaded drawings, detects potential compliance issues, and generates detailed reports with violation highlights and resolution suggestions.</p>

<em>Figure: System workflow from upload to compliance reporting</em>

<h3>Key Features</h3>
<ul>
  <li>Drawing upload interface with file validation</li>
  <li>Automated compliance scanning engine</li>
  <li>Violation detection with rule references</li>
  <li>PDF/Excel report generation</li>
  <li>Dashboard for tracking submissions</li>
</ul>

<h2>Technical Implementation</h2>
<h3>Processing Methodology</h3>
<p>The system uses computer vision algorithms to analyze drawing elements against the compliance rules database. Key steps include:</p>
<ol>
  <li>Drawing preprocessing (vectorization, layer separation)</li>
  <li>Element detection (exit routes, fire compartments)</li>
  <li>Dimensional analysis (travel distances, exit widths)</li>
  <li>Rule-based compliance checking</li>
</ol>

<h3>Challenges Faced</h3>
<ul>
  <li><strong>Drawing Interpretation:</strong> Handling various CAD formats and scales required robust conversion pipelines</li>
  <li><strong>Rule Codification:</strong> Translating 300+ pages of FSD regulations into machine-readable logic</li>
  <li><strong>Accuracy Validation:</strong> Achieving 92%+ detection accuracy across diverse drawing styles</li>
</ul>

<h2>System Components</h2>
<pre>
1. Frontend: React-based upload portal
2. Processing: Python-based analysis engine
3. Database: PostgreSQL for rule storage
4. Reporting: PDF generation module
</pre>

<h2>Usage</h2>
<p>Users upload drawings through the web interface. The system processes files within 2-5 minutes (depending on drawing complexity) and returns a compliance report with:</p>
<ul>
  <li>Identified violations</li>
  <li>Relevant code sections</li>
  <li>Recommended corrective actions</li>
</ul>
