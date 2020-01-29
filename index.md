<!DOCTYPE html>
<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <title>
      Matei Zaharia 
    </title>
    <link href="./Matei Zaharia_files/css" rel="stylesheet">
    <link rel="stylesheet" href="./Matei Zaharia_files/basic-profile.css" media="all">
    <meta name="description" content="">
    <meta name="keywords" content="">
    
  </head>
  <body>
    <div id="wrap">
      <div id="sidebar">

      <div id="photo">
      <a href="./Matei Zaharia_files/matei.jpg"><img src="./Matei Zaharia_files/matei.jpg" style="border: none; width:220px;" alt="Matei Zaharia"></a>
      </div>
      
        <ul>          
          <li><a href="https://cs.stanford.edu/~matei/#interests">Interests</a></li>
          <li><a href="https://cs.stanford.edu/~matei/#teaching">Teaching</a></li>
          <li><a href="https://cs.stanford.edu/~matei/#publications">Publications</a></li>
          <li><a href="https://cs.stanford.edu/~matei/#awards">Awards</a></li>
          <li><a href="https://cs.stanford.edu/~matei/#opensource">Code</a></li>
        </ul>
      </div>
      <div id="content">
        <h1 id="matei-zaharia">Matei Zaharia</h1>

<p>Assistant Professor, Computer Science<br>
<a href="mailto:matei@cs.stanford.edu">matei@cs.stanford.edu</a> |
<a href="https://scholar.google.com/citations?user=I1EvjZsAAAAJ">Google Scholar</a> |
<a href="https://twitter.com/matei_zaharia">Twitter</a><br>
Office: <a href="https://campus-map.stanford.edu/?id=07-450&amp;lat=37.4292581632993&amp;lng=-122.1747304424173&amp;zoom=16&amp;srch=gates%20computer%20science">Gates 412</a><br>
<a href="https://cs.stanford.edu/~matei/cv.pdf">Curriculum Vitæ</a></p>

<p>I’m an assistant professor at Stanford CS, where I work on computer systems and machine learning as part of <a href="http://dawn.cs.stanford.edu/">Stanford DAWN</a>.
I’m also co-founder and Chief Technologist of <a href="https://databricks.com/">Databricks</a>, a data and AI platform startup.
Before joining Stanford, I was an assistant professor at MIT.</p>

<p><a name="interests"></a>
<strong>Interests:</strong> I’m interested in computer systems for emerging large-scale workloads such as machine learning, big data analytics and cloud computing.
In <a href="http://dawn.cs.stanford.edu/">DAWN</a>, we’re working on <a href="https://arxiv.org/pdf/1705.07538.pdf">infrastructure for usable machine learning</a> to make it dramatically easier to bring ML applications to production: these issues are often much larger obstacles than ML algorithms in practice.
My work includes <a href="https://cs.stanford.edu/~matei/papers/2017/cidr_weld.pdf">software runtimes</a>, <a href="https://cs.stanford.edu/~matei/papers/2018/mlsys_model_assertions.pdf">quality assurance tools</a> and <a href="https://cs.stanford.edu/~matei/papers/2017/vldb_noscope.pdf">systems optimizations for ML</a>.
Beyond usability, I am intersted in data privacy as the flipside to big data, and have worked on systems that can provide scalable privacy for <a href="https://cs.stanford.edu/~matei/papers/2015/sosp_vuvuzela.pdf">communication</a>, <a href="https://cs.stanford.edu/~matei/papers/2017/nsdi_splinter.pdf">Internet queries</a> and <a href="https://cs.stanford.edu/~matei/papers/2017/hotnets_diy.pdf">SaaS applications</a>.</p>

<p><strong>Impact:</strong> Our group works closely with the open source community to test and publish our ideas.
During my PhD, I started the <a href="https://spark.apache.org/">Apache Spark</a> project,
which is now one of the most widely used frameworks for distributed data processing, and co-started other
widely used datacenter software such as <a href="https://mesos.apache.org/">Apache Mesos</a>,
<a href="https://cs.stanford.edu/~matei/papers/2014/socc_tachyon.pdf">Alluxio</a>, and <a href="https://cs.stanford.edu/~matei/papers/2013/sosp_spark_streaming.pdf">Spark Streaming</a>.
At Stanford, we developed <a href="https://dawn.cs.stanford.edu/benchmark">DAWNBench</a>, a machine learning performance competition
that drew submissions from the top industry groups and influenced the industry-standard <a href="https://mlperf.org/">MLPerf</a>,
and we are continuing to develop open source software such as 
<a href="https://weld.rs/">Weld</a>, <a href="https://cs.stanford.edu/~matei/papers/2018/vldb_sparser.pdf">Sparser</a>, <a href="https://cs.stanford.edu/~matei/papers/2017/vldb_noscope.pdf">NoScope</a>, and 
<a href="https://cs.stanford.edu/~matei/papers/2019/vldb_macrobase_diff.pdf">MacroBase DIFF</a>.</p>

<p>Some of our work has been featured in <a href="https://www.wired.com/2013/06/yahoo-amazon-amplab-spark/">Wired</a> (<a href="https://www.wired.com/2013/06/yahoo-amazon-amplab-spark/">1</a>/<a href="https://www.wired.com/2013/03/google-borg-twitter-mesos/">2</a>/<a href="https://www.wired.com/2014/10/startup-crunches-100-terabytes-data-record-23-minutes/">3</a>),
<a href="http://fortune.com/2015/09/25/apache-spark-survey/">Fortune</a>,
<a href="https://techcrunch.com/2015/03/19/on-the-growth-of-apache-spark/">TechCrunch</a>,
<a href="https://www.wsj.com/articles/newer-software-aims-to-crunch-hadoops-numbers-1434326008">The Wall Street Journal</a>,
<a href="https://www.theregister.co.uk/2018/05/02/mlperf_ai_benchmark/">The Register</a>,
<a href="https://arstechnica.com/information-technology/2016/08/building-a-new-tor-that-withstands-next-generation-state-surveillance/">Ars Technica</a>,
<a href="https://motherboard.vice.com/en_us/article/aekd7p/now-that-its-easy-to-encrypt-our-chats-encrypting-metadata-comes-next">Motherboard</a>,
<a href="https://www.zdnet.com/article/apache-spark-sets-out-to-standardize-distributed-machine-learning-training-execution-and-deployment/">ZDNet</a>,
<a href="https://www.economist.com/business/2019/09/05/technology-firms-vie-for-billions-in-data-analytics-contracts">The Economist</a>, and
<a href="https://www.forbes.com/sites/janakirammsv/2018/07/02/databricks-aims-to-simplify-building-machine-learning-models-through-mlflow/#5c16d013e4ed">Forbes</a>.</p>

<h2><a name="teaching">Teaching</a></h2>

<ul>
  <li><a href="https://canvas.stanford.edu/courses/114221">CS 320 (Value of Data and AI):</a> winter 2020.</li>
  <li><a href="http://web.stanford.edu/class/cs245/">CS 245 (Principles of Data-Intensive Systems):</a> winter 2020.</li>
  <li><a href="http://web.stanford.edu/class/cs245/spr2019/">CS 245 (Principles of Data-Intensive Systems):</a> spring 2019.</li>
  <li><a href="http://cs349d.stanford.edu/">CS 349D (Cloud Computing Technology):</a> fall 2018.</li>
  <li><a href="https://canvas.stanford.edu/courses/73958">CS 149 (Parallel Computing):</a> winter 2018.</li>
  <li><a href="http://cs349d.stanford.edu/">CS 349D (Cloud Computing Technology):</a> fall 2017.</li>
  <li><a href="http://web.stanford.edu/class/cs341/">CS 341 (Projects in Mining Massive Datasets):</a> spring 2017.</li>
</ul>

<h2><a name="students">PhD Students and Postdocs</a></h2>

<ul>
  <li><a href="http://firasabuzaid.com/">Firas Abuzaid</a> (with <a href="http://www.bailis.org/">Peter Bailis</a>)</li>
  <li><a href="http://www.codycoleman.com/">Cody Coleman</a>  (with <a href="http://www.bailis.org/">Peter Bailis</a>)</li>
  <li><a href="https://research.google/people/TrevorGale/">Trevor Gale</a></li>
  <li><a href="https://ddkang.github.io/">Daniel Kang</a>  (with <a href="http://www.bailis.org/">Peter Bailis</a>)</li>
  <li><a href="https://deeptir.me/">Deepti Raghavan</a> (with <a href="http://csl.stanford.edu/~pal/">Phil Levis</a>)</li>
  <li><a href="https://cs.uwaterloo.ca/~fkazhami/">Fiodar Kazhamiaka</a> (with <a href="http://www.bailis.org/">Peter Bailis</a>)</li>
  <li><a href="http://petereliaskraft.net/">Peter Kraft</a> (with <a href="http://www.bailis.org/">Peter Bailis</a>)</li>
  <li><a href="http://cs.stanford.edu/~deepakn/">Deepak Narayanan</a></li>
  <li><a href="http://shoumik.xyz/">Shoumik Palkar</a></li>
  <li><a href="https://www.linkedin.com/in/keshav-santhanam-2917a0105/">Keshav Santhanam</a></li>
  <li><a href="http://cs.stanford.edu/~prthaker/">Pratiksha Thaker</a></li>
  <li><a href="http://cs.stanford.edu/~jjthomas/">James Thomas</a> (with <a href="https://graphics.stanford.edu/~hanrahan/">Pat Hanrahan</a>)</li>
</ul>

<h2><a name="publications">Publications</a></h2>

<h3 id="2020">2020</h3>

<ul>
  <li><a href="https://cs.stanford.edu/~matei/papers/2020/vldb_blazeit.pdf">BlazeIt: Optimizing Declarative Aggregation and Limit Queries for Neural Network-Based Video Analytics</a>. D. Kang, P. Bailis and M. Zaharia. <em>To appear at VLDB 2020</em>. <a href="https://arxiv.org/pdf/1805.01046.pdf">(preprint)</a></li>
  <li><a href="https://cs.stanford.edu/~matei/papers/2020/vldb_oblidb.pdf">ObliDB: Oblivious Query Processing for Secure Databases</a>. S. Eskandarian and M. Zaharia. <em>To appear at VLDB 2020</em>.</li>
  <li><a href="javascript:void">Selection via Proxy: Efficient Data Selection for Deep Learning</a>. C. Coleman, C. Yeh, S. Mussmann, B. Mirzasoleiman, P. Bailis, P. Liang, J. Leskovec and M. Zaharia. <em>To appear at ICLR 2020</em>. <a href="https://arxiv.org/pdf/1906.11829.pdf">(preprint)</a></li>
  <li><a href="javascript:void">Fleet: A Framework for Massively Parallel Streaming on FPGAs</a>. J. Thomas, P. Hanrahan and M. Zaharia. <em>To appear at ASPLOS 2020</em>.</li>
  <li><a href="javascript:void">Willump: A Statistically-Aware End-to-end Optimizer for Machine Learning Inference</a>. P. Kraft, D. Kang, D. Narayanan, S. Palkar, P. Bailis and M. Zaharia. <em>To appear at MLSys 2020.</em> <a href="https://arxiv.org/pdf/1906.01974.pdf">(preprint)</a></li>
  <li><a href="javascript:void">Model Assertions for Monitoring and Improving ML Models</a>. D. Kang, D. Raghavan, P. Bailis and M. Zaharia. <em>To appear at MLSys 2020.</em></li>
  <li><a href="javascript:void">Improving the Accuracy, Scalability, and Performance of Graph Neural Networks with Roc</a>. Z. Jia, S. Lin, M. Gao, M. Zaharia and A. Aiken. <em>To appear at MLSys 2020.</em></li>
  <li><a href="javascript:void">MLPerf Training Benchmark</a>. P. Mattson, C. Cheng, C. Coleman, G. Diamos, P. Micikevicius, D. Patterson, H. Tang, G-Y. Wei, P. Bailis, V. Bittorf, D. Brooks, D. Chen, D. Dutta, U. Gupta, K. Hazelwood, A. Hock, X. Huang, B. Jia, D. Kang, D. Kanter, N. Kumar, J. Liao, D. Narayanan, T. Oguntebi, G. Pekhimenko, L. Pentecost, V. J. Reddi, T. Robie, T. St. John, C-J. Wu, L. Xu, C. Young, and M. Zaharia. <em>To appear at MLSys 2020.</em> <a href="https://arxiv.org/pdf/1910.01500.pdf">(preprint)</a></li>
</ul>

<p><strong style="font-size:1.4em;"><a href="https://cs.stanford.edu/~matei/publications">Full Publication List</a></strong></p>

<p><strong style="font-size:1.4em;"><a href="https://arxiv.org/search/cs?searchtype=author&amp;query=Zaharia%2C+Matei">Recent Preprints</a></strong></p>

<h2><a name="awards">Awards</a></h2>

<ul>
  <li>Presidential Early Career Award for Scientists and Engineers (PECASE), 2019</li>
  <li><a href="https://nsf.gov/awardsearch/showAward?AWD_ID=1651570">NSF CAREER Award</a>, 2017</li>
  <li><a href="https://www.vmware.com/radius/systems-research-award-2016/">VMware Systems Research Award</a>, 2016</li>
  <li>Google Faculty Research Award, 2015</li>
  <li><a href="http://awards.acm.org/award_winners/zaharia_7692208.cfm">ACM Doctoral Dissertation Award</a>, 2014</li>
  <li>U. Waterloo Faculty of Mathematics Young Alumni Achievement Medal, 2014</li>
  <li><a href="http://sortbenchmark.org/">Daytona GraySort World Record</a>, 2014</li>
  <li>David J. Sakrison Prize for Research, UC Berkeley, 2013</li>
  <li>Best Paper Awards at SIGCOMM 2012 and NSDI 2012</li>
</ul>

<h2><a name="service">Service</a></h2>

<ul>
  <li><strong>Program Co-Chair:</strong> <a href="https://mlops-systems.github.io/">MLOps Workshop at MLSys 2020</a>, <a href="https://mlsys.org/Conferences/2019/">SysML 2019</a>.</li>
  <li><strong>Program Committee Member:</strong> NeurIPS 2019, SIGMOD 2019, OSDI 2018, SIGMOD 2018, NSDI 2018, SoCC 2017, SIGMOD 2016, SIGCOMM 2016, NSDI 2015.</li>
  <li><strong>Invited Reviewer:</strong> CACM, TPDS, VLDB.</li>
</ul>

<h2><a name="opensource">Open Source</a></h2>

<p>Almost all of my work is open source:</p>

<ul>
  <li>The <a href="https://spark.apache.org/">Spark engine</a> became an Apache project at <a href="https://spark.apache.org/">spark.apache.org</a>. We have also open sourced subsequent
projects including <a href="http://shark.cs.berkeley.edu/">Shark</a>,
<a href="https://spark.apache.org/sql">Spark SQL</a>, <a href="http://spark.apache.org/mllib">MLlib</a>,
<a href="https://github.com/graphframes/graphframes">GraphFrames</a>
and <a href="http://spark.apache.org/streaming">Spark Streaming</a>.</li>
  <li><a href="https://mlflow.org/">MLflow</a> is a new open source project for managing the machine learning development process.</li>
  <li>The <a href="https://mesos.apache.org/">Mesos cluster manager</a> is a top-level Apache project.</li>
  <li><a href="https://cs.stanford.edu/~matei/papers/2008/osdi_late.pdf">LATE</a> straggler mitigation and
the <a href="https://cs.stanford.edu/~matei/papers/2010/eurosys_delay_scheduling.pdf">Hadoop Fair Scheduler</a>
are included in Apache Hadoop.</li>
  <li>The <a href="http://snap.cs.berkeley.edu/">SNAP sequence aligner</a> is available on <a href="https://github.com/amplab/snap">GitHub</a>.</li>
</ul>

<p>More recent projects are available on the <a href="https://www.weld.rs/">Weld</a> and <a href="https://github.com/stanford-futuredata">FutureData</a> websites.</p>


        <p class="credits">
          Adapted from a template by <a href="http://andreasviklund.com/">Andreas Viklund</a>.
        </p>
      </div>
    </div>
  

</body></html>
