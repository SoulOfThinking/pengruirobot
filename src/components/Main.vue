<template>
  <head>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.1/css/all.min.css">
    <!-- <meta charset="UTF-8"> -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  </head>
  <div class="main">
    <div class="section header">
      <!-- <div class="subtitle"><img class="mat-icon" src="/logo.png">LongVIL: Long-Horizon Visual Imitation Learning</div>
        -->
      <div class="subtitle">LongVIL: Long-Horizon Visual Imitation Learning</div>
      <div class="subtitle">
        via Plan and Code Reflection
      </div>


      <div class="author-list">
        <!-- <span class="author">
          <el-link href="https://zmling22.github.io/">Quan Chen</el-link>
          <span class="ind">1 &#9733;</span>,
        </span>
        <span class="author">
          <el-link href="https://zhigao2017.github.io/">Zhi Gao</el-link>
          <span class="ind">1 &#9733;</span>
        </span> -->
        <span class="author">
          <el-link>Quan Chen</el-link>
          <span class="ind">1,2 &#9733;</span>,
        </span>
        <span class="author">
          <el-link>Chenrui Shi</el-link>
          <span class="ind">1 &#9733;</span>,
        </span>
        <span class="author">
          <el-link>Qi Chen</el-link>
          <span class="ind">1,2</span>,
        </span>
        <span class="author">
          <el-link>Yuwei Wu</el-link>
          <span class="ind">1</span>,
        </span>
        <span class="author">
          <el-link>Zhi Gao</el-link>
          <span class="ind">1 </span>,
        </span>
        <br>
        <span class="author">
          <el-link>Xintong Zhang</el-link>
          <span class="ind">1 </span>,
        </span>
        <span class="author">
          <el-link>Rui Gao</el-link>
          <span class="ind">1,2 </span>,
        </span>
        <span class="author">
          <el-link>Kun Wu</el-link>
          <span class="ind">3 </span>,
        </span>
        <span class="author">
          <el-link>Yunde Jia</el-link>
          <span class="ind">2 </span>
        </span>
        <!-- <span class="author">
          <el-link href="https://wu-yuwei-bit.github.io/">Yuwei Wu</el-link>
          <span class="ind">&#9993;3,4</span>,
        </span>
        <span class="author">
          <el-link href="https://scholar.google.com/citations?user=Sl6TV7gAAAAJ&hl=en">Yunde Jia</el-link>
          <span class="ind">4,3</span>,
        </span> -->
        <br>
      </div>
      <div class="author-list">
        <span class="org">
          <span class="ind">1</span>
          Beijing Key Laboratory of Intelligent Information Technology, School of Computer Science and Technology, Beijing Institute of Technology
        </span>
        <br>
        <span class="org">
          <span class="ind">2</span>
          Guangdong Laboratory of Machine Perception and Intelligent Computing, Shenzhen MSU-BIT University
        </span>
        <br>
        <span class="org">
          <span class="ind">3</span>
          Beijing Innovation Center of Humanoid Robotics
        </span>
      </div>

      <span class="link-block">
        <a href="https://arxiv.org/abs/2509.05368" class="external-link button is-normal is-rounded is-dark">
          <span class="icon">
            <svg xmlns="http://www.w3.org/2000/svg" width="1.0em" height="1.0em" viewBox="0 0 24 24">
              <path fill="currentColor"
                d="M3.842 0a1 1 0 0 0-.922.608c-.153.369-.044.627.294 1.111l6.919 8.36l-1.023 1.106a1.04 1.04 0 0 0 .003 1.423l1.23 1.313l-5.44 6.444c-.28.3-.453.823-.297 1.199a1.025 1.025 0 0 0 .959.635a.91.91 0 0 0 .689-.34l5.783-6.126l7.49 8.005a.85.85 0 0 0 .684.26a.96.96 0 0 0 .877-.615c.158-.377-.017-.75-.306-1.14L13.73 13.9l1.064-1.13a.963.963 0 0 0 .009-1.316L4.633.464S4.26.01 3.867 0zm0 .272h.017c.218.005.487.272.564.364l.005.006l.005.005l10.17 10.99a.69.69 0 0 1-.008.946l-1.066 1.133l-1.498-1.772l-8.6-10.39c-.328-.472-.352-.619-.26-.841a.73.73 0 0 1 .671-.44Zm14.341 1.57a.88.88 0 0 0-.655.242l-5.696 6.158l1.694 1.832l5.309-6.514c.325-.433.479-.66.325-1.029a1.12 1.12 0 0 0-.977-.689m-7.655 12.282l1.318 1.414l-5.786 6.13a.65.65 0 0 1-.496.26a.75.75 0 0 1-.706-.467c-.112-.269.036-.687.244-.909l.005-.005l.005-.006z" />
            </svg>
          </span>
          <span>arXiv</span>
        </a>
      </span>
      <span class="link-block">
        <a href="https://github.com/chenquan2002/LongVIL" class="external-link button is-normal is-rounded is-dark">
          <span class="icon">
            <i class="fab fa-github"></i>
          </span>
          <span>Code</span>
        </a>
      </span>

      <!-- Data Link. need changing -->
      <span class="link-block">

        <a target="_blank" href="https://huggingface.co/datasets/cq838/LongVILBench"
          class="external-link button is-normal is-rounded is-dark">
          <span class="icon">
            <i class="fa fa-database"></i>
          </span>
          <span>Data</span>
        </a>
      </span>
      <div class="link-buttons">

        
  <!-- arXiv -->
 
</div>

      <!-- <span class="link-block">
        <a href="file/clova_cvpr24_poster.pdf"
            class="external-link button is-normal is-rounded is-dark">
          <span class="icon">
            <i class="fas fa-file-pdf"></i>
          </span>
          <span>Submited to NeurIPS 2025</span>
        </a>
      </span> -->

      <!-- <span class="link-block">
            <a href="file/clova_slides.pdf"
               class="external-link button is-normal is-rounded is-dark">
              <span class="icon">
                  <i class="fas fa-file-pdf"></i>
              </span>
              <span>Slides</span>
            </a>
          </span> -->

    </div>

    <!-- <div class="tldr">
      <p><b>TL;DR</b> 
        The paper proposes MemoryEQA, a memory-centric embodied question answering (EQA) framework with the MT-HM3D dataset for evaluate memory ability of EQA models, 
        boosting performance by 19.8% on MT-HM3D from baseline model.</p>
    </div> -->

    <!-- <div class="section">
      <el-card class="teaser">
        <el-image src="./logo.png" style="width: 300px; height: auto;"></el-image>
      </el-card>
    </div> -->

    <div class="section">
    <div class="section-title">Abstract</div>
    <p class="intro">
        Learning from long-horizon demonstrations with complex action sequences presents significant challenges for visual imitation learning, particularly in understanding temporal relationships of actions and spatial relationships between objects. 
        In this paper, we propose a new agent framework that incorporates two dedicated reflection modules to enhance both plan and code generation. 
        The plan generation module produces an initial action sequence, which is then verified by the plan reflection module to ensure temporal coherence and spatial alignment with the demonstration video. 
        The code generation module translates the plan into executable code, while the code reflection module verifies and refines the generated code to ensure correctness and consistency with the generated plan. 
        These two reflection modules jointly enable the agent to detect and correct errors in both the plan generation and code generation, improving performance in tasks with intricate temporal and spatial dependencies. 
        To support systematic evaluation, we introduce LongVILBench, a benchmark comprising 300 human demonstrations with action sequences of up to 18 steps. LongVILBench emphasizes temporal and spatial complexity across multiple task types. 
        Experimental results demonstrate that existing methods perform poorly on this benchmark, whereas our new framework establishes a strong baseline for long-horizon visual imitation learning.
    </p>
</div>
    <!-- <div class="section">
      <el-card class="teaser">
        <el-image src="./overview.png"></el-image>
      </el-card>
    </div>
     -->

<div class="section">
  <div class="section-title">Method Overview</div>
  <!-- 插入图片 -->
  <el-card class="teaser">
    <el-image src="./overview.png"></el-image>
  </el-card>
  <p class="intro">
    The LongVIL framework is designed to enhance long-horizon visual imitation learning tasks by incorporating two reflection modules: plan reflection and code reflection. The agent framework includes four key modules: the plan generation module, which produces initial action sequences; the plan reflection module, which verifies temporal and spatial consistency; the code generation module, which translates the plan into executable code; and the code reflection module, which ensures that the generated code aligns with the plan. This process of planning, verification, and correction allows LongVIL to better handle long-horizon tasks with complex temporal and spatial relationships.
  </p>
</div>





  <!-- <div class="section">
  <div class="section-title">LongVILBench</div>
  <div class="intro">
    <p><b>Why a new benchmark?</b> Long-horizon imitation tasks demand robust temporal ordering and precise spatial grounding, where early mistakes cascade and current VLM-based pipelines often misalign plans or hallucinate actions. Existing datasets skew short (few steps), lack explicit difficulty stratification, or offer limited spatial relations, making them insufficient to test planning, reasoning, and execution in long sequences. LongVILBench fills this gap with real human demonstrations, rich spatial predicates, and tiered difficulty to stress long-horizon reasoning.</p>

    <p><b>What is LongVILBench?</b> A real-world video benchmark of <b>150</b> tasks recorded under <b>two visual conditions</b> (clean ↔ complex), giving <b>300</b> demonstrations and <b>2,332</b> annotated atomic actions (avg. 7.8 per video). Tasks span <b>three levels</b> by action length: L1 (1–4), L2 (5–8), L3 (9–18). We use <b>4 atomic actions</b> (pick, place, open, close) over <b>14 objects</b> (vegetables, geometric blocks, containers) and <b>6 spatial relations</b> (left, right, front, behind, on top of, into). Each plan is validated in simulation and reenacted twice to provide controlled vs. challenging visual settings.</p>

    <ul style="margin-left:1em;">
      <li><b>Categories:</b> block manipulation, tabletop cleanup, vegetable sorting</li>
      <li><b>Actions:</b> pick, place, open, close</li>
      <li><b>Spatial relations:</b> left, right, front, behind, on top of, into</li>
      <li><b>Objects:</b> 14 total (vegetables, blocks, drawers/containers)</li>
      <li><b>Visual conditions:</b> Clean (fixed lighting/camera) & Complex (varied lighting/viewpoint)</li>
      <li><b>Scale:</b> 150 tasks × 2 conditions = 300 videos; 2,332 actions (7.8 per video)</li>
    </ul>

    <el-card class="teaser" style="max-width:700px; margin:20px auto;">
      <el-image src="./stats.png"></el-image>
      <p style="text-align:center; font-size:0.9em; color:#666;">(a) Direction distribution, (b) Object distribution, (c) Action distribution, (d) KDE Plot of Video Duration per Task Level.</p>
    </el-card>

    <p><b>Evaluation metrics.</b> We report <b>EMA</b> (exact sequence match), <b>FSA</b> (final state correctness of the environment), and <b>SMS</b> (prefix length ratio measuring how far a method proceeds correctly before deviating). These jointly assess sequence fidelity, goal attainment, and step-wise robustness for long-horizon execution.</p>
  </div>
</div> -->


 


<div class="section">
  <div class="section-title">LongVILBench</div>
  <div class="intro">
    <p><b>Why a new benchmark?</b> Long-horizon imitation tasks demand robust temporal ordering and precise spatial grounding, where early mistakes cascade and current VLM-based pipelines often misalign plans or hallucinate actions. Existing datasets skew short (few steps), lack explicit difficulty stratification, or offer limited spatial relations, making them insufficient to test planning, reasoning, and execution in long sequences. LongVILBench fills this gap with real human demonstrations, rich spatial predicates, and tiered difficulty to stress long-horizon reasoning.</p>

    <p><b>What is LongVILBench?</b> A real-world video benchmark of <b>150</b> tasks recorded under <b>two visual conditions</b> (clean ↔ complex), giving <b>300</b> demonstrations and <b>2,332</b> annotated atomic actions (avg. 7.8 per video). Tasks span <b>three levels</b> by action length: L1 (1–4), L2 (5–8), L3 (9–18). We use <b>4 atomic actions</b> (pick, place, open, close) over <b>14 objects</b> (vegetables, geometric blocks, containers) and <b>6 spatial relations</b> (left, right, front, behind, on top of, into). Each plan is validated in simulation and reenacted twice to provide controlled vs. challenging visual settings.</p>

    <ul style="margin-left:1em;">
      <li><b>Categories:</b> block manipulation, tabletop cleanup, vegetable sorting</li>
      <li><b>Actions:</b> pick, place, open, close</li>
      <li><b>Spatial relations:</b> left, right, front, behind, on top of, into</li>
      <li><b>Objects:</b> 14 total (vegetables, blocks, drawers/containers)</li>
      <li><b>Visual conditions:</b> Clean (fixed lighting/camera) & Complex (varied lighting/viewpoint)</li>
      <li><b>Scale:</b> 150 tasks × 2 conditions = 300 videos; 2,332 actions (7.8 per video)</li>
    </ul>

    <!-- 统计图（你已提供的 stats.png） -->
    <el-card class="teaser" style="max-width:700px; margin:20px auto;">
      <el-image src="./stats.png"></el-image>
      <p style="text-align:center; font-size:0.9em; color:#666;">
        (a) Direction distribution, (b) Object distribution, (c) Action distribution, (d) KDE Plot of Video Duration per Task Level.
      </p>
    </el-card>

    <!-- 交互式视频展示（3 levels × 3 tasks × 2 conditions = 18） -->
    <div class="section-title" style="font-size:1.6em; margin-top:36px;">Benchmark Gallery</div>
    <div class="intro" style="margin-bottom:12px;">Interactively browse examples across difficulty, task type, and visual condition.</div>

    <el-card class="teaser" shadow="never" style="max-width:840px; margin:0 auto 16px auto;">
      <div class="lvb-controls">
        <!-- Level -->
        <div class="lvb-control">
          <label>Level</label>
          <el-select v-model="lvb.level" size="small" style="width:130px;" placeholder="Level">
            <el-option label="Level 1" value="L1" />
            <el-option label="Level 2" value="L2" />
            <el-option label="Level 3" value="L3" />
          </el-select>
        </div>

        <!-- Task -->
        <div class="lvb-control">
          <label>Task</label>
          <el-select v-model="lvb.task" size="small" style="width:180px;" placeholder="Task">
            <el-option label="Blocks" value="blocks" />
            <el-option label="Vegetables" value="vegetables" />
            <el-option label="Cleanup" value="cleanup" />
          </el-select>
        </div>

        <!-- Condition -->
        <div class="lvb-control">
          <label>Condition</label>
          <el-select v-model="lvb.cond" size="small" style="width:160px;" placeholder="Condition">
            <el-option label="Clean" value="clean" />
            <el-option label="Complex" value="complex" />
          </el-select>
        </div>
      </div>

      <div style="margin-top:14px; text-align:center;">
        <!-- 播放窗口：根据选择的三元组切换视频 -->
        <video
          :key="currentVideo.src"
          :src="currentVideo.src"
          controls
          preload="metadata"
          style="width:100%; max-width:820px; border-radius:12px; outline:none;"
        ></video>
        <div style="margin-top:8px; font-size:0.9em; color:#666;">
          {{ currentVideo.caption }}
        </div>
      </div>
    </el-card>

    <p><b>Evaluation metrics.</b> We report <b>EMA</b> (exact sequence match), <b>FSA</b> (final state correctness of the environment), and <b>SMS</b> (prefix length ratio measuring how far a method proceeds correctly before deviating). These jointly assess sequence fidelity, goal attainment, and step-wise robustness for long-horizon execution.</p>
  </div>
</div>

<div class="section" id="results">
  <div class="section-title">Evaluation & Results</div>
  <div class="intro">
    We evaluate LongVIL on <b>LongVILBench</b> with three metrics — <b>EMA</b> (Exact Match Accuracy), 
    <b>FSA</b> (Final State Accuracy), and <b>SMS</b> (Step-wise Matching Score). 
    Results below summarize overall SOTA comparison, performance by difficulty level, and ablation studies.
  </div>

  
<!-- 合并后的综合结果表：L1/L2/L3/Total × (EMA/FSA/SMS) -->
<div class="subsection-title">Overall and Per-level Results (EMA / FSA / SMS)</div>
<div class="intro">
  Results on <b>L1–L3</b> and <b>Total</b> across three metrics. Best scores per column are highlighted in bold.
</div>

<el-table :data="mergedRows" border stripe class="result-table">
  <el-table-column prop="method" label="Method" width="240" fixed="left"></el-table-column>

  <!-- L1 -->
  <el-table-column label="L1" align="center">
    <el-table-column label="EMA" width="100">
      <template #default="{ row }">
        <span :class="{ best: row.l1_ema === maxVals.l1_ema }">{{ fmt(row.l1_ema) }}</span>
      </template>
    </el-table-column>
    <el-table-column label="FSA" width="100">
      <template #default="{ row }">
        <span :class="{ best: row.l1_fsa === maxVals.l1_fsa }">{{ fmt(row.l1_fsa) }}</span>
      </template>
    </el-table-column>
    <el-table-column label="SMS" width="100">
      <template #default="{ row }">
        <span :class="{ best: row.l1_sms === maxVals.l1_sms }">{{ fmt(row.l1_sms) }}</span>
      </template>
    </el-table-column>
  </el-table-column>

  <!-- L2 -->
  <el-table-column label="L2" align="center">
    <el-table-column label="EMA" width="100">
      <template #default="{ row }">
        <span :class="{ best: row.l2_ema === maxVals.l2_ema }">{{ fmt(row.l2_ema) }}</span>
      </template>
    </el-table-column>
    <el-table-column label="FSA" width="100">
      <template #default="{ row }">
        <span :class="{ best: row.l2_fsa === maxVals.l2_fsa }">{{ fmt(row.l2_fsa) }}</span>
      </template>
    </el-table-column>
    <el-table-column label="SMS" width="100">
      <template #default="{ row }">
        <span :class="{ best: row.l2_sms === maxVals.l2_sms }">{{ fmt(row.l2_sms) }}</span>
      </template>
    </el-table-column>
  </el-table-column>

  <!-- L3 -->
  <el-table-column label="L3" align="center">
    <el-table-column label="EMA" width="100">
      <template #default="{ row }">
        <span :class="{ best: row.l3_ema === maxVals.l3_ema }">{{ fmt(row.l3_ema) }}</span>
      </template>
    </el-table-column>
    <el-table-column label="FSA" width="100">
      <template #default="{ row }">
        <span :class="{ best: row.l3_fsa === maxVals.l3_fsa }">{{ fmt(row.l3_fsa) }}</span>
      </template>
    </el-table-column>
    <el-table-column label="SMS" width="100">
      <template #default="{ row }">
        <span :class="{ best: row.l3_sms === maxVals.l3_sms }">{{ fmt(row.l3_sms) }}</span>
      </template>
    </el-table-column>
  </el-table-column>

  <!-- Total -->
  <el-table-column label="Total" align="center">
    <el-table-column label="EMA" width="110">
      <template #default="{ row }">
        <span :class="{ best: row.t_ema === maxVals.t_ema }">{{ fmt(row.t_ema) }}</span>
      </template>
    </el-table-column>
    <el-table-column label="FSA" width="110">
      <template #default="{ row }">
        <span :class="{ best: row.t_fsa === maxVals.t_fsa }">{{ fmt(row.t_fsa) }}</span>
      </template>
    </el-table-column>
    <el-table-column label="SMS" width="110">
      <template #default="{ row }">
        <span :class="{ best: row.t_sms === maxVals.t_sms }">{{ fmt(row.t_sms) }}</span>
      </template>
    </el-table-column>
  </el-table-column>
</el-table>

  



  <!-- 3) 不同视觉条件（Clean / Complex, Total） -->
  <div class="subsection-title">Results under Visual Conditions</div>
  <div class="intro">All methods drop under complex visuals; LongVIL keeps the highest scores across metrics.</div>
  <!-- <el-table :data="condRows" border stripe class="result-table">
    <el-table-column prop="method" label="Method" width="240"></el-table-column>
    <el-table-column prop="clean_ema" label="Clean · EMA"></el-table-column>
    <el-table-column prop="clean_fsa" label="Clean · FSA"></el-table-column>
    <el-table-column prop="clean_sms" label="Clean · SMS"></el-table-column>
    <el-table-column prop="complex_ema" label="Complex · EMA"></el-table-column>
    <el-table-column prop="complex_fsa" label="Complex · FSA"></el-table-column>
    <el-table-column prop="complex_sms" label="Complex · SMS"></el-table-column>
  </el-table> -->

  <el-table :data="condRows" border stripe class="result-table">
  <el-table-column prop="method" label="Method" width="240"></el-table-column>

  <el-table-column label="Clean · EMA">
    <template #default="{ row }">
      <span :class="{ best: isBest(row.clean_ema, maxCond.clean_ema) }">{{ fmt(row.clean_ema) }}</span>
    </template>
  </el-table-column>

  <el-table-column label="Clean · FSA">
    <template #default="{ row }">
      <span :class="{ best: isBest(row.clean_fsa, maxCond.clean_fsa) }">{{ fmt(row.clean_fsa) }}</span>
    </template>
  </el-table-column>

  <el-table-column label="Clean · SMS">
    <template #default="{ row }">
      <span :class="{ best: isBest(row.clean_sms, maxCond.clean_sms) }">{{ fmt(row.clean_sms) }}</span>
    </template>
  </el-table-column>

  <el-table-column label="Complex · EMA">
    <template #default="{ row }">
      <span :class="{ best: isBest(row.complex_ema, maxCond.complex_ema) }">{{ fmt(row.complex_ema) }}</span>
    </template>
  </el-table-column>

  <el-table-column label="Complex · FSA">
    <template #default="{ row }">
      <span :class="{ best: isBest(row.complex_fsa, maxCond.complex_fsa) }">{{ fmt(row.complex_fsa) }}</span>
    </template>
  </el-table-column>

  <el-table-column label="Complex · SMS">
    <template #default="{ row }">
      <span :class="{ best: isBest(row.complex_sms, maxCond.complex_sms) }">{{ fmt(row.complex_sms) }}</span>
    </template>
  </el-table-column>
</el-table>


  <!-- 4) 消融实验（Total 列） -->
  <div class="subsection-title">Ablation Study (Total)</div>
  <div class="intro">
    Visual reflection improves temporal/spatial alignment; code reflection improves execution consistency — combining both gives the best performance.
  </div>
  <!-- <el-table :data="ablationRows" border stripe class="result-table">
    <el-table-column prop="variant" label="Variant" width="300"></el-table-column>
    <el-table-column prop="ema" label="EMA ↑" width="140"></el-table-column>
    <el-table-column prop="fsa" label="FSA ↑" width="140"></el-table-column>
    <el-table-column prop="sms" label="SMS ↑" width="140"></el-table-column>
    <el-table-column prop="delta" label="Δ vs. Base"></el-table-column>
  </el-table> -->

  <el-table :data="ablationRows" border stripe class="result-table">
  <el-table-column prop="variant" label="Variant" width="300"></el-table-column>

  <el-table-column label="EMA ↑" width="140">
    <template #default="{ row }">
      <span :class="{ best: isBest(row.ema, maxAbl.ema) }">{{ fmt(row.ema) }}</span>
    </template>
  </el-table-column>

  <el-table-column label="FSA ↑" width="140">
    <template #default="{ row }">
      <span :class="{ best: isBest(row.fsa, maxAbl.fsa) }">{{ fmt(row.fsa) }}</span>
    </template>
  </el-table-column>

  <el-table-column label="SMS ↑" width="140">
    <template #default="{ row }">
      <span :class="{ best: isBest(row.sms, maxAbl.sms) }">{{ fmt(row.sms) }}</span>
    </template>
  </el-table-column>

  <el-table-column prop="delta" label="Δ vs. Base"></el-table-column>
</el-table>





  <!-- 5) 合并演示视频（放在最后） -->
  <!-- <div class="subsection-title">Representative Video</div>
  <div class="intro">Combined demo across clean/complex conditions and sim/real executions.</div>
  <el-card class="teaser" shadow="never" style="max-width:900px; margin:12px auto 0;">
    <video src="./results/combined_result.mp4" controls preload="metadata" class="single-video"></video>
  </el-card>

  <div class="intro" style="margin-top:12px;">
    <b>Takeaways.</b> LongVIL delivers higher sequence fidelity (EMA), better goal attainment (FSA), and longer correct prefixes (SMS), 
    especially on Level-3 and under complex visuals. 
  </div> -->


  <div class="intro">Combined demo across clean/complex conditions and sim/real executions.</div>
<el-card class="teaser" shadow="never" style="max-width:900px; margin:12px auto 0;">
  <div style="display:flex; gap:12px; justify-content:center;">
    <video src="/results/block.mp4" controls preload="metadata" class="dual-video" style="flex:1; max-width:50%;"></video>
    <video src="/results/clean.mp4" controls preload="metadata" class="dual-video" style="flex:1; max-width:50%;"></video>
  </div>
</el-card>



</div>







   


  </div>

  <section class="section" id="BibTeX" style="text-align: left;">
    <div class="container is-max-desktop content" style="max-width: 100%; margin: 0 auto;">
      <h3 class="title" style="font-size: small;">
        BibTeX
      </h3>
      <div class="bibtex-container">
        <pre><code class="language-bibtex">
    @inproceedings{gao2025multi,
      title={Long-Horizon Visual Imitation Learning via Plan and Code Reflection},
      author={Quan Chen and Chenrui Shi and Qi Chen and Yuwei Wu and Zhi Gao and Xintong Zhang and Rui Gao and Kun Wu and Yunde Jia},
      booktitle={arXiv preprint arXiv:2509.05368}
    }
</code></pre>
      </div>
    </div>
  </section>


  <div class="footer">
    This website is inspired by <el-link href="https://mathvista.github.io/">MathVista</el-link> and <el-link
      href="https://nerfies.github.io/">Nerfies</el-link>.
  </div>
</template>

<script setup>
import Dialog from './Dialog.vue'

import { onMounted, ref } from 'vue'

const dataset1 = ref([])
const loadData1 = async () => {
  const resp1 = await fetch('./data/demo-100k.json')
  dataset1.value = await resp1.json()
}

const dataset2 = ref([])
const loadData2 = async () => {
  const resp2 = await fetch('./data/demo-1m.json')
  dataset2.value = await resp2.json()
}

const dataset3 = ref([])
const loadData3 = async () => {
  const resp3 = await fetch('./data/demo-bench.json')
  dataset3.value = await resp3.json()
}

onMounted(() => {
  loadData1(),
    loadData2(),
    loadData3()
})

// —— LongVILBench：视频筛选逻辑 ——
// 需要引入 reactive / computed
// 若你上面已有 import { onMounted, ref } from 'vue'，请改为：
import {  reactive, computed } from 'vue'

// 三元组选择状态（默认值可改）
const lvb = reactive({
  level: 'L1',          // 'L1' | 'L2' | 'L3'
  task: 'blocks',       // 'blocks' | 'vegetables' | 'cleanup'
  cond: 'clean',        // 'clean' | 'complex'
})

// 18 个视频的索引表（把 src 改成你的实际文件路径/文件名）
const videoIndex = [
  // Level 1
  { level:'L1', task:'blocks',     cond:'clean',   src:'./videos/L1_blocks_clean.mp4',   caption:'Level 1 · Blocks · Clean' },
  { level:'L1', task:'blocks',     cond:'complex', src:'./videos/L1_blocks_complex.mp4', caption:'Level 1 · Blocks · Complex' },
  { level:'L1', task:'vegetables', cond:'clean',   src:'./videos/L1_vegetables_clean.mp4',   caption:'Level 1 · Vegetables · Clean' },
  { level:'L1', task:'vegetables', cond:'complex', src:'./videos/L1_vegetables_complex.mp4', caption:'Level 1 · Vegetables · Complex' },
  { level:'L1', task:'cleanup',    cond:'clean',   src:'./videos/L1_cleanup_clean.mp4',   caption:'Level 1 · Cleanup · Clean' },
  { level:'L1', task:'cleanup',    cond:'complex', src:'./videos/L1_cleanup_complex.mp4', caption:'Level 1 · Cleanup · Complex' },

  // Level 2
  { level:'L2', task:'blocks',     cond:'clean',   src:'./videos/L2_blocks_clean.mp4',   caption:'Level 2 · Blocks · Clean' },
  { level:'L2', task:'blocks',     cond:'complex', src:'./videos/L2_blocks_complex.mp4', caption:'Level 2 · Blocks · Complex' },
  { level:'L2', task:'vegetables', cond:'clean',   src:'./videos/L2_vegetables_clean.mp4',   caption:'Level 2 · Vegetables · Clean' },
  { level:'L2', task:'vegetables', cond:'complex', src:'./videos/L2_vegetables_complex.mp4', caption:'Level 2 · Vegetables · Complex' },
  { level:'L2', task:'cleanup',    cond:'clean',   src:'./videos/L2_cleanup_clean.mp4',   caption:'Level 2 · Cleanup · Clean' },
  { level:'L2', task:'cleanup',    cond:'complex', src:'./videos/L2_cleanup_complex.mp4', caption:'Level 2 · Cleanup · Complex' },

  // Level 3
  { level:'L3', task:'blocks',     cond:'clean',   src:'./videos/L3_blocks_clean.mp4',   caption:'Level 3 · Blocks · Clean' },
  { level:'L3', task:'blocks',     cond:'complex', src:'./videos/L3_blocks_complex.mp4', caption:'Level 3 · Blocks · Complex' },
  { level:'L3', task:'vegetables', cond:'clean',   src:'./videos/L3_vegetables_clean.mp4',   caption:'Level 3 · Vegetables · Clean' },
  { level:'L3', task:'vegetables', cond:'complex', src:'./videos/L3_vegetables_complex.mp4', caption:'Level 3 · Vegetables · Complex' },
  { level:'L3', task:'cleanup',    cond:'clean',   src:'./videos/L3_cleanup_clean.mp4',   caption:'Level 3 · Cleanup · Clean' },
  { level:'L3', task:'cleanup',    cond:'complex', src:'./videos/L3_cleanup_complex.mp4', caption:'Level 3 · Cleanup · Complex' },
]

// 根据 selectors 计算当前视频
const currentVideo = computed(() => {
  return videoIndex.find(v => v.level === lvb.level && v.task === lvb.task && v.cond === lvb.cond) || {
    src: '',
    caption: 'No video found for current selection.'
  }
})



/* ======= Results data from the paper ======= */
/* 1) Overall (Total) — Table 2 */

// —— 合并表数据（Table 2）
const mergedRows = [
  { method: 'GPTforRobots-GPT-4o',
    l1_ema: 0.34, l1_fsa: 0.34, l1_sms: 0.8050,
    l2_ema: 0.14, l2_fsa: 0.14, l2_sms: 0.4803,
    l3_ema: 0.15, l3_fsa: 0.15, l3_sms: 0.4324,
    t_ema: 0.21,  t_fsa: 0.21,  t_sms: 0.5760,
  },
  { method: 'SeeDo-GPT-4o',
    l1_ema: 0.35, l1_fsa: 0.35, l1_sms: 0.5425,
    l2_ema: 0.06, l2_fsa: 0.06, l2_sms: 0.2198,
    l3_ema: 0.00, l3_fsa: 0.00, l3_sms: 0.1132,
    t_ema: 0.14,  t_fsa: 0.14,  t_sms: 0.2919,
  },
  { method: 'Ours-Base-Qwen',
    l1_ema: 0.68, l1_fsa: 0.68, l1_sms: 0.8185,
    l2_ema: 0.28, l2_fsa: 0.28, l2_sms: 0.5660,
    l3_ema: 0.12, l3_fsa: 0.12, l3_sms: 0.4649,
    t_ema: 0.36,  t_fsa: 0.36,  t_sms: 0.6063,
  },
  { method: 'Ours-Reflection-Qwen',
    l1_ema: 0.73, l1_fsa: 0.73, l1_sms: 0.8660,
    l2_ema: 0.30, l2_fsa: 0.30, l2_sms: 0.5380,
    l3_ema: 0.17, l3_fsa: 0.17, l3_sms: 0.4904,
    t_ema: 0.40,  t_fsa: 0.40,  t_sms: 0.6348,
  },
  { method: 'Ours-Base-GPT-4o',
    l1_ema: 0.76, l1_fsa: 0.76, l1_sms: 0.8700,
    l2_ema: 0.34, l2_fsa: 0.34, l2_sms: 0.5635,
    l3_ema: 0.19, l3_fsa: 0.19, l3_sms: 0.4217,
    t_ema: 0.43,  t_fsa: 0.43,  t_sms: 0.6184,
  },
  { method: 'Ours-Reflection-GPT-4o',
    l1_ema: 0.81, l1_fsa: 0.81, l1_sms: 0.9000,
    l2_ema: 0.40, l2_fsa: 0.40, l2_sms: 0.6183,
    l3_ema: 0.25, l3_fsa: 0.26, l3_sms: 0.4649,  // L3 FSA 修正为 0.26
    t_ema: 0.4867, t_fsa: 0.49, t_sms: 0.6611,
  },
];


// 计算每列的最大值，用于加粗
const maxVals = {
  l1_ema: Math.max(...mergedRows.map(r => r.l1_ema)),
  l1_fsa: Math.max(...mergedRows.map(r => r.l1_fsa)),
  l1_sms: Math.max(...mergedRows.map(r => r.l1_sms)),
  l2_ema: Math.max(...mergedRows.map(r => r.l2_ema)),
  l2_fsa: Math.max(...mergedRows.map(r => r.l2_fsa)),
  l2_sms: Math.max(...mergedRows.map(r => r.l2_sms)),
  l3_ema: Math.max(...mergedRows.map(r => r.l3_ema)),
  l3_fsa: Math.max(...mergedRows.map(r => r.l3_fsa)),
  l3_sms: Math.max(...mergedRows.map(r => r.l3_sms)),
  t_ema:  Math.max(...mergedRows.map(r => r.t_ema)),
  t_fsa:  Math.max(...mergedRows.map(r => r.t_fsa)),
  t_sms:  Math.max(...mergedRows.map(r => r.t_sms)),
}

// 数字格式化（保留两位小数）
const fmt = (v) => (v === null || v === undefined) ? '—' : Number(v).toFixed(2)


/* 3) Visual conditions — Table 4 */
const condRows = [
  { method: 'GPTforRobots-GPT-4o',    clean_ema: 0.22, clean_fsa: 0.22, clean_sms: 0.59, complex_ema: 0.20, complex_fsa: 0.20, complex_sms: 0.56 }, // :contentReference[oaicite:19]{index=19}
  { method: 'SeeDo-GPT-4o',           clean_ema: 0.14, clean_fsa: 0.14, clean_sms: 0.29, complex_ema: 0.13, complex_fsa: 0.13, complex_sms: 0.29 }, // :contentReference[oaicite:20]{index=20}
  { method: 'Ours-Base-Qwen',         clean_ema: 0.41, clean_fsa: 0.41, clean_sms: 0.63, complex_ema: 0.32, complex_fsa: 0.32, complex_sms: 0.58 }, // :contentReference[oaicite:21]{index=21}
  { method: 'Ours-Reflection-Qwen',   clean_ema: 0.44, clean_fsa: 0.44, clean_sms: 0.66, complex_ema: 0.36, complex_fsa: 0.36, complex_sms: 0.61 }, // :contentReference[oaicite:22]{index=22}
  { method: 'Ours-Base-GPT-4o',       clean_ema: 0.47, clean_fsa: 0.47, clean_sms: 0.65, complex_ema: 0.39, complex_fsa: 0.39, complex_sms: 0.58 }, // :contentReference[oaicite:23]{index=23}
  { method: 'Ours-Reflection-GPT-4o', clean_ema: 0.55, clean_fsa: 0.56, clean_sms: 0.71, complex_ema: 0.42, complex_fsa: 0.42, complex_sms: 0.61 }, // :contentReference[oaicite:24]{index=24}
]

/* 4) Ablation — Table 3（Total 列） */
const ablationRows = [
  { variant: 'A · Base',                         ema: 0.43,   fsa: 0.43,   sms: 0.6184, delta: '—' },            // :contentReference[oaicite:25]{index=25}
  { variant: 'B · +Keyframe Completion',        ema: 0.44,   fsa: 0.45,   sms: 0.6439, delta: '+0.01 / +0.02 / +0.0255' }, // :contentReference[oaicite:26]{index=26}
  { variant: 'C · +Rv (Visual Reflection)',     ema: 0.4667, fsa: 0.47,   sms: 0.6486, delta: '+0.0367 / +0.04 / +0.0302' }, // :contentReference[oaicite:27]{index=27}
  { variant: 'D · +Rc (Code Reflection, Full)', ema: 0.4867, fsa: 0.49,   sms: 0.6611, delta: '+0.0567 / +0.06 / +0.0427' }, // :contentReference[oaicite:28]{index=28}
]

// 高亮判断（容差避免浮点误差）
const isBest = (v, max, eps = 1e-9) => Math.abs(Number(v) - Number(max)) < eps

// Visual Conditions：各列最大值
const maxCond = {
  clean_ema:   Math.max(...condRows.map(r => r.clean_ema)),
  clean_fsa:   Math.max(...condRows.map(r => r.clean_fsa)),
  clean_sms:   Math.max(...condRows.map(r => r.clean_sms)),
  complex_ema: Math.max(...condRows.map(r => r.complex_ema)),
  complex_fsa: Math.max(...condRows.map(r => r.complex_fsa)),
  complex_sms: Math.max(...condRows.map(r => r.complex_sms)),
}

// Ablation：各指标最大值
const maxAbl = {
  ema: Math.max(...ablationRows.map(r => r.ema)),
  fsa: Math.max(...ablationRows.map(r => r.fsa)),
  sms: Math.max(...ablationRows.map(r => r.sms)),
}


</script>






<style scoped>
.main {
  text-align: center;
  color: #333;
}
.best { font-weight: 700; }


/* .header {
  margin: 60px 0 0 0 !important;
} */
.header {
  margin: 60px auto 0 auto !important; /* 保证上下居中 */
  width: 100%; /* 确保header宽度自适应 */
  text-align: center; /* 保证文字居中 */
}

.title {
  font-size: 5em;
}

.subtitle {
  font-size: 2.5em;
  color: #555;
}

.author-list {
  margin-top: 20px;
}

.author a {
  font-size: 1.2em;
  font-weight: normal;
  color: #337ecc;
}

.org {
  margin: 0 4px 0 4px;
}

.ind {
  font-size: 0.8em;
  vertical-align: super;
}

/* .section {
  margin: 50px 0;
} */
 .section {
  margin: 50px auto;
  max-width: 900px;
  padding: 0 20px;
}

.tldr {
  text-align: left;
  font-size: 1em;
  max-width: 1360px;
  line-height: 150%;
}

.section-title {
  margin: 20px;
  font-size: 2em;
  font-weight: bold;
}

.conference {
  text-align: center;
  margin: 20px;
  font-size: 1.5em;
  color: #665;
}

.uns {
  text-decoration: underline;
}

.mat-icon {
  width: 0.8em;
  height: 0.8em;
  margin-right: 0.2em;
}

.teaser {
  max-width: 840px;
  margin: 0 auto;
}

.stats-img {
  height: 300px;
}

.stats-img-1 {
  max-width: 67%;
  max-height: 95%;
  object-fit: contain;
  margin: 0 auto;
  display: block;
}

.intro {
  text-align: justify;
  font-size: 1em;
  max-width: 1360px;
  line-height: 150%;
}

.link-block a {
  margin-top: 5px;
  margin-bottom: 5px;
}

.example-dialog {
  width: 800px;
}

.footer {
  color: #aaa;
  margin: 100px 0 60px 0;
}


/* The top button */
.external-link {
  display: inline-block;
  padding: 8px 16px;
  /* inner margin */
  margin: 4px;
  /* outer margin */
  border: 1px solid #9a9c9e;
  /* color of border */
  border-radius: 9px;
  background-color: #8a8b8b;
  color: white;
  text-decoration: none;
  font-size: 20px;
  transition: background-color 0.3s;
}
.conference {
  text-align: center;
  margin: 20px;
  font-size: 1.5em;
  color: #665;
}
.external-link:hover {
  background-color: #8e8f90;
}

.external-link .icon {
  margin-right: 8px;
}

.external-link .fas {
  font-size: 18px;
}

.bibtex-container {
  background-color: #e1e4e9;
  /* Change background color to match the theme */
  padding: 1em;
  /* Add padding for better readability */
  border-radius: 5px;
  /* Add border radius for rounded corners */
  text-align: left;
  white-space: pre;
  /* Preserve formatting and prevent line breaks */
  overflow-x: auto;
  /* Add horizontal scroll bar */
}

pre {
  margin: 0;
}

code {
  font-family: 'Courier New', Courier, monospace;
  /* Change font to monospace */
  color: #0a0b0b;
  /* Change text color to match the theme */
}
.lvb-controls {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  margin-bottom: 6px;
}
.lvb-control {
  display: flex;
  align-items: center;
  gap: 8px;
}
.lvb-control label {
  font-weight: bold;
}

.subsection-title {
  margin: 18px 0 6px;
  font-size: 1.4em;
  font-weight: 700;
  text-align: left;
}
.result-table {
  max-width: 900px;
  margin: 8px auto 16px;
  text-align: left;
}
.single-video {
  width: 100%;
  max-width: 860px;
  border-radius: 10px;
  outline: none;
}




/* —— 统一顶部按钮尺寸，仅影响 .external-link —— */
/* 让三颗按钮一条线对齐、居中 */
.link-block {
  display: inline-block;
  vertical-align: middle;    /* 避免基线不一致 */
  margin: 4px 10px;          /* 横向间距可按需调 */
}

/* 按钮内部用 flex 居中，去掉由 margin 造成的不均匀 */
.external-link {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 10px;                 /* 统一图标与文字间距 */
  line-height: 1;            /* 防止行高把内容顶偏 */
}

/* 固定“图标框”的宽高，让三颗按钮里的文字起点一致 */
.external-link .icon,
.external-link .fa,          /* Font Awesome 基类 */
.external-link .fas,         /* FA 5 solid */
.external-link .fab,         /* FA 5 brand (GitHub) */
.external-link svg {
  width: 28px;               /* 图标占位宽度，可改 24/32 */
  height: 28px;
  flex: 0 0 28px;            /* 不拉伸不压缩 */
  display: inline-flex;
  align-items: center;
  justify-content: center;
}

/* 去掉你原本给 .icon 的右外边距，统一用 gap 控制 */
.external-link .icon { margin-right: 0 !important; }

/* 防止 arXiv 的 SVG 以文本基线对齐导致“下沉” */
.external-link svg { vertical-align: middle; }


</style>
