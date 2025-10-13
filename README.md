# ai-agent-opensorce

<p dir="auto">A curated collection of AI agent use cases across industries, showcasing practical applications and linking to open-source projects for implementation. Explore how AI agents are transforming industries like healthcare, finance, education, and more! 🤖✨</p>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">📋 Table of Contents</h2><a id="user-content--table-of-contents" class="anchor" aria-label="Permalink: 📋 Table of Contents" href="#-table-of-contents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><a href="#introduction">Introduction</a></li>
<li><a href="#-industry-usecase-mindmap">Industry Usecase</a></li>
<li><a href="#use-case-table">Use Case Table</a></li>
<li><a href="#framework-wise-usecases">Framework Wise UseCase</a>
<ul dir="auto">
<li><a href="#framework-name-crewai">CrewAI UseCase</a></li>
<li><a href="#framework-name-autogen">AutoGen UseCase</a></li>
<li><a href="#framework-name-agno">Agno UseCase</a></li>
<li><a href="#framework-name-langgraph">Langgraph UseCase</a></li>
</ul>
</li>
<li><a href="#contributing">Contributing</a></li>
<li><a href="#license">License</a></li>
</ul>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">🧠 Introduction</h2><a id="user-content--introduction" class="anchor" aria-label="Permalink: 🧠 Introduction" href="#-introduction"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">Artificial Intelligence (AI) agents are revolutionizing the way industries operate. From personalized learning to financial trading bots, AI agents bring efficiency, innovation, and scalability. This repository provides:</p>
<ul dir="auto">
<li>A categorized list of industries where AI agents are making an impact.</li>
<li>Detailed use cases with links to open-source projects for implementation.</li>
</ul>
<p dir="auto">Whether you're a developer, researcher, or business enthusiast, this repository is your go-to resource for AI agent inspiration and learning.</p>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">🏭 Industry UseCase MindMap</h2><a id="user-content--industry-usecase-mindmap" class="anchor" aria-label="Permalink: 🏭 Industry UseCase MindMap" href="#-industry-usecase-mindmap"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/ashishpatel26/500-AI-Agents-Projects/blob/main/images/industry_usecase1.png"><img src="/ashishpatel26/500-AI-Agents-Projects/raw/main/images/industry_usecase1.png" alt="" style="max-width: 100%;"></a></p>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">🧩 Use Case Table</h2><a id="user-content--use-case-table" class="anchor" aria-label="Permalink: 🧩 Use Case Table" href="#-use-case-table"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th>Use Case</th>
<th>Industry</th>
<th>Description</th>
<th>Code Github</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>HIA (Health Insights Agent)</strong></td>
<td>Healthcare</td>
<td>analyses medical reports and provide health insights.</td>
<td><a href="https://github.com/harshhh28/hia.git"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>AI Health Assistant</strong></td>
<td>Healthcare</td>
<td>Diagnoses and monitors diseases using patient data.</td>
<td><a href="https://github.com/ahmadvh/AI-Agents-for-Medical-Diagnostics.git"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>Automated Trading Bot</strong></td>
<td>Finance</td>
<td>Automates stock trading with real-time market analysis.</td>
<td><a href="https://github.com/MingyuJ666/Stockagent.git"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>Virtual AI Tutor</strong></td>
<td>Education</td>
<td>Provides personalized education tailored to users.</td>
<td><a href="https://github.com/hqanhh/EduGPT.git"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>24/7 AI Chatbot</strong></td>
<td>Customer Service</td>
<td>Handles customer queries around the clock.</td>
<td><a href="https://github.com/NirDiamant/GenAI_Agents/blob/main/all_agents_tutorials/customer_support_agent_langgraph.ipynb"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>Product Recommendation Agent</strong></td>
<td>Retail</td>
<td>Suggests products based on user preferences and history.</td>
<td><a href="https://github.com/microsoft/RecAI"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>Self-Driving Delivery Agent</strong></td>
<td>Transportation</td>
<td>Optimizes routes and autonomously delivers packages.</td>
<td><a href="https://github.com/sled-group/driVLMe"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>Factory Process Monitoring Agent</strong></td>
<td>Manufacturing</td>
<td>Monitors production lines and ensures quality control.</td>
<td><a href="https://github.com/yuchenxia/llm4ias"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>Property Pricing Agent</strong></td>
<td>Real Estate</td>
<td>Analyzes market trends to determine property prices.</td>
<td><a href="https://github.com/AleksNeStu/ai-real-estate-assistant"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>Smart Farming Assistant</strong></td>
<td>Agriculture</td>
<td>Provides insights on crop health and yield predictions.</td>
<td><a href="https://github.com/mohammed97ashraf/LLM_Agri_Bot"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>Energy Demand Forecasting Agent</strong></td>
<td>Energy</td>
<td>Predicts energy usage to optimize grid management.</td>
<td><a href="https://github.com/yecchen/MIRAI"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>Content Personalization Agent</strong></td>
<td>Entertainment</td>
<td>Recommends personalized media based on preferences.</td>
<td><a href="https://github.com/crosleythomas/MirrorGPT"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>Legal Document Review Assistant</strong></td>
<td>Legal</td>
<td>Automates document review and highlights key clauses.</td>
<td><a href="https://github.com/firica/legalai"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>Recruitment Recommendation Agent</strong></td>
<td>Human Resources</td>
<td>Suggests best-fit candidates for job openings.</td>
<td><a href="https://github.com/sentient-engineering/jobber"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>Virtual Travel Assistant</strong></td>
<td>Hospitality</td>
<td>Plans travel itineraries based on preferences.</td>
<td><a href="https://github.com/nirbar1985/ai-travel-agent"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>AI Game Companion Agent</strong></td>
<td>Gaming</td>
<td>Enhances player experience with real-time assistance.</td>
<td><a href="https://github.com/onjas-buidl/LLM-agent-game"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>Real-Time Threat Detection Agent</strong></td>
<td>Cybersecurity</td>
<td>Identifies potential threats and mitigates attacks.</td>
<td><a href="https://github.com/NVISOsecurity/cyber-security-llm-agents"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>E-commerce Personal Shopper Agent</strong></td>
<td>E-commerce</td>
<td>Helps customers find products they’ll love.</td>
<td><a href="https://github.com/Hoanganhvu123/ShoppingGPT"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>Logistics Optimization Agent</strong></td>
<td>Supply Chain</td>
<td>Plans efficient delivery routes and manages inventory.</td>
<td><a href="https://github.com/microsoft/OptiGuide"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>Vibe Hacking Agent</strong></td>
<td>Cybersecurity</td>
<td>Autonomous Multi-Agent Based Red Team Testing Service.</td>
<td><a href="https://github.com/PurpleAILAB/Decepticon"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>MediSuite-Ai-Agent</strong></td>
<td>Health insurance</td>
<td>A medical ai agent that helps automating the process of hospitals / insurance claiming workflow.</td>
<td><a href="https://github.com/MahmoudRabea13/MediSuite-Ai-Agent"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td><strong>Lina-Egyptian-Medical-Chatbot</strong></td>
<td>Health insurance</td>
<td>A medical ai agent that helps automating the process of hospitals / insurance claiming workflow.</td>
<td><a href="https://github.com/MahmoudRabea13/MediSuite-Ai-Agent"><img src="https://camo.githubusercontent.com/e2fe6a6e3380679809f388855b2035b54aca9e2194461b02fc41c44f4117ae6e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f436f64652d4769744875622d626c61636b3f6c6f676f3d676974687562" alt="GitHub" data-canonical-src="https://img.shields.io/badge/Code-GitHub-black?logo=github" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">Framework wise Usecases</h2><a id="user-content-framework-wise-usecases" class="anchor" aria-label="Permalink: Framework wise Usecases" href="#framework-wise-usecases"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<hr>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><strong>Framework Name</strong>: <strong>CrewAI</strong></h3><a id="user-content-framework-name-crewai" class="anchor" aria-label="Permalink: Framework Name: CrewAI" href="#framework-name-crewai"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th>Use Case</th>
<th>Industry</th>
<th>Description</th>
<th>GitHub</th>
</tr>
</thead>
<tbody>
<tr>
<td>📧 Email Auto Responder Flow</td>
<td>🗣️ Communication</td>
<td>Automates email responses based on predefined criteria to enhance communication efficiency.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/flows/email_auto_responder_flow"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>📝 Meeting Assistant Flow</td>
<td>🛠️ Productivity</td>
<td>Assists in organizing and managing meetings, including scheduling and agenda preparation.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/flows/meeting_assistant_flow"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>🔄 Self Evaluation Loop Flow</td>
<td>👥 Human Resources</td>
<td>Facilitates self-assessment processes within an organization, aiding in performance reviews.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/flows/self_evaluation_loop_flow"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>📈 Lead Score Flow</td>
<td>💼 Sales</td>
<td>Evaluates and scores potential leads to prioritize outreach in sales strategies.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/flows/lead-score-flow"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>📊 Marketing Strategy Generator</td>
<td>📢 Marketing</td>
<td>Develops marketing strategies by analyzing market trends and audience data.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/marketing_strategy"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>📝 Job Posting Generator</td>
<td>🧑‍💼 Recruitment</td>
<td>Creates job postings by analyzing job requirements, aiding in recruitment processes.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/job-posting"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>🔄 Recruitment Workflow</td>
<td>🧑‍💼 Recruitment</td>
<td>Streamlines the recruitment process by automating various tasks involved in hiring.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/recruitment"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>🔍 Match Profile to Positions</td>
<td>🧑‍💼 Recruitment</td>
<td>Matches candidate profiles to suitable job positions to enhance recruitment efficiency.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/match_profile_to_positions"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>📸 Instagram Post Generator</td>
<td>📱 Social Media</td>
<td>Generates and schedules Instagram posts automatically, streamlining social media management.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/instagram_post"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>🌐 Landing Page Generator</td>
<td>💻 Web Development</td>
<td>Automates the creation of landing pages for websites, facilitating web development tasks.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/landing_page_generator"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>🎮 Game Builder Crew</td>
<td>🎮 Game Development</td>
<td>Assists in the development of games by automating certain aspects of game creation.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/game-builder-crew"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>💹 Stock Analysis Tool</td>
<td>💰 Finance</td>
<td>Provides tools for analyzing stock market data to assist in financial decision-making.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/stock_analysis"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>🗺️ Trip Planner</td>
<td><g-emoji class="g-emoji" alias="airplane">✈️</g-emoji> Travel</td>
<td>Assists in planning trips by organizing itineraries and managing travel details.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/trip_planner"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>🎁 Surprise Trip Planner</td>
<td><g-emoji class="g-emoji" alias="airplane">✈️</g-emoji> Travel</td>
<td>Plans surprise trips by selecting destinations and activities based on user preferences.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/surprise_trip"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>📚 Write a Book with Flows</td>
<td>✍️ Creative Writing</td>
<td>Assists authors in writing books by providing structured workflows and writing assistance.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/flows/write_a_book_with_flows"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>🎬 Screenplay Writer</td>
<td>✍️ Creative Writing</td>
<td>Aids in writing screenplays by offering templates and guidance for script development.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/screenplay_writer"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>✅ Markdown Validator</td>
<td>📄 Documentation</td>
<td>Validates Markdown files to ensure proper formatting and adherence to standards.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/markdown_validator"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>🧠 Meta Quest Knowledge</td>
<td>📚 Knowledge Management</td>
<td>Manages and organizes knowledge related to Meta Quest, facilitating information retrieval.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/meta_quest_knowledge"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>🤖 NVIDIA Models Integration</td>
<td>🤖 AI Integration</td>
<td>Integrates NVIDIA AI models into workflows to enhance computational capabilities.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/integrations/nvidia_models"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>🗂️ Prep for a Meeting</td>
<td>🛠️ Productivity</td>
<td>Assists in preparing for meetings by organizing materials and setting agendas.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/prep-for-a-meeting"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>🛠️Starter Template</td>
<td>🛠️ Development</td>
<td>Provides a starter template for new projects to streamline the setup process.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/crews/starter_template"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>🔗CrewAI + LangGraph Integration</td>
<td>🤖 AI Integration</td>
<td>Demonstrates integration between CrewAI and LangGraph for enhanced workflow automation.</td>
<td><a href="https://github.com/crewAIInc/crewAI-examples/tree/main/integrations/CrewAI-LangGraph"><img src="https://camo.githubusercontent.com/68e9e8ce3d8027781e5e96f2c3e7bddeffcffd6801c9576eb9ddc31398ed2901/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d5265706f7369746f72792d626c7565" alt="GitHub" data-canonical-src="https://img.shields.io/badge/GitHub-Repository-blue" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><strong>Framework Name</strong>: <strong>Autogen</strong></h3><a id="user-content-framework-name-autogen" class="anchor" aria-label="Permalink: Framework Name: Autogen" href="#framework-name-autogen"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<blockquote>
<p dir="auto"><strong>Code Generation, Execution, and Debugging</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th>Use Case</th>
<th>Industry</th>
<th>Description</th>
<th>Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td>🤖 Automated Task Solving with Code Generation, Execution &amp; Debugging</td>
<td>💻 Software Development</td>
<td>Demonstrates automated task-solving by generating, executing, and debugging code.</td>
<td><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_auto_feedback_from_code_execution" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>🧑‍💻 Automated Code Generation and Question Answering with Retrieval Augmented Agents</td>
<td>💻 Software Development</td>
<td>Generates code and answers questions using retrieval-augmented methods.</td>
<td><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_RetrieveChat" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td>🧠 Automated Code Generation and Question Answering with Qdrant-based Retrieval</td>
<td>💻 Software Development</td>
<td>Utilizes Qdrant for enhanced retrieval-augmented agent performance.</td>
<td><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_RetrieveChat_qdrant" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<blockquote>
<p dir="auto"><strong>Multi-Agent Collaboration (&gt;3 Agents)</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th align="left">Use Case</th>
<th align="left">Industry</th>
<th align="left">Description</th>
<th align="left">Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">🤝 Automated Task Solving by Group Chat (3 members, 1 manager)</td>
<td align="left">🤝 Collaboration</td>
<td align="left">Demonstrates group task-solving via multi-agent collaboration.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_groupchat" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">📊 Automated Data Visualization by Group Chat (3 members, 1 manager)</td>
<td align="left">📊 Data Analysis</td>
<td align="left">Uses multi-agent collaboration to create data visualizations.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_groupchat_vis" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧩 Automated Complex Task Solving by Group Chat (6 members, 1 manager)</td>
<td align="left">🤝 Collaboration</td>
<td align="left">Solves complex tasks collaboratively with a larger group of agents.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_groupchat_research" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧑‍💻 Automated Task Solving with Coding &amp; Planning Agents</td>
<td align="left">🛠️ Planning &amp; Development</td>
<td align="left">Combines coding and planning agents for solving tasks effectively.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_planning.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">📐 Automated Task Solving with Transition Paths Specified in a Graph</td>
<td align="left">🤝 Collaboration</td>
<td align="left">Uses predefined transition paths in a graph for solving tasks.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/docs/notebooks/agentchat_groupchat_finite_state_machine" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 Running a Group Chat as an Inner-Monologue via the SocietyOfMindAgent</td>
<td align="left">🧠 Cognitive Sciences</td>
<td align="left">Simulates inner-monologue for problem-solving using group chats.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_society_of_mind" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🔧 Running a Group Chat with Custom Speaker Selection Function</td>
<td align="left">🤝 Collaboration</td>
<td align="left">Implements a custom function for speaker selection in group chats.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_groupchat_customized" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<blockquote>
<p dir="auto"><strong>Sequential Multi-Agent Chats</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th align="left">Use Case</th>
<th align="left">Industry</th>
<th align="left">Description</th>
<th align="left">Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">🔄 Solving Multiple Tasks in a Sequence of Chats Initiated by a Single Agent</td>
<td align="left">🔄 Workflow Automation</td>
<td align="left">Automates sequential task-solving with a single initiating agent.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_multi_task_chats" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">⏳ Async-solving Multiple Tasks in a Sequence of Chats Initiated by a Single Agent</td>
<td align="left">🔄 Workflow Automation</td>
<td align="left">Handles asynchronous task-solving in a sequence of chats initiated by one agent.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_multi_task_async_chats" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🤝 Solving Multiple Tasks in a Sequence of Chats Initiated by Different Agents</td>
<td align="left">🔄 Workflow Automation</td>
<td align="left">Facilitates sequential task-solving with different agents initiating each chat.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchats_sequential_chats" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<blockquote>
<p dir="auto"><strong>Nested Chats</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th align="left">Use Case</th>
<th align="left">Industry</th>
<th align="left">Description</th>
<th align="left">Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">🧠 Solving Complex Tasks with Nested Chats</td>
<td align="left">🧠 Problem Solving</td>
<td align="left">Uses nested chats to solve hierarchical and complex problems.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_nestedchat" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🔄 Solving Complex Tasks with A Sequence of Nested Chats</td>
<td align="left">🧠 Problem Solving</td>
<td align="left">Demonstrates sequential task-solving using nested chats.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_nested_sequential_chats" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🏭 OptiGuide for Solving a Supply Chain Optimization Problem with Nested Chats</td>
<td align="left">🏭 Supply Chain Optimization</td>
<td align="left">Showcases how to solve supply chain optimization problems using nested chats, a coding agent, and a safeguard agent.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_nestedchat_optiguide" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">♟️ Conversational Chess with Nested Chats and Tool Use</td>
<td align="left">🎮 Gaming</td>
<td align="left">Explores the use of nested chats for playing conversational chess with integrated tools.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_nested_chats_chess" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<blockquote>
<p dir="auto"><strong>Application</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th align="left">Use Case</th>
<th align="left">Industry</th>
<th align="left">Description</th>
<th align="left">Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">🔄 Automated Continual Learning from New Data</td>
<td align="left">📊 Machine Learning</td>
<td align="left">Continuously learns from new data inputs for adaptive AI.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_stream.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🏭 OptiGuide - Coding, Tool Using, Safeguarding &amp; Question Answering for Supply Chain Optimization</td>
<td align="left">🏭 Supply Chain Optimization</td>
<td align="left">Highlights a solution combining coding, tool use, and safeguarding for supply chain optimization.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_nestedchat_optiguide" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🤖 AutoAnny - A Discord bot built using AutoGen</td>
<td align="left">💬 Communication Tools</td>
<td align="left">Showcases the development of a Discord bot using AutoGen for enhanced interaction.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/tree/main/samples/apps/auto-anny"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<blockquote>
<p dir="auto"><strong>Tools</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th align="left">Use Case</th>
<th align="left">Industry</th>
<th align="left">Description</th>
<th align="left">Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">🌐 Web Search: Solve Tasks Requiring Web Info</td>
<td align="left">🔍 Information Retrieval</td>
<td align="left">Searches the web to gather information required for completing tasks.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_web_info.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🔧 Use Provided Tools as Functions</td>
<td align="left">🛠️ Tool Integration</td>
<td align="left">Demonstrates how to use pre-provided tools as callable functions in AutoGen.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_function_call_currency_calculator" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🔗 Use Tools via Sync and Async Function Calling</td>
<td align="left">🛠️ Tool Integration</td>
<td align="left">Illustrates synchronous and asynchronous tool usage within AutoGen workflows.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_function_call_async" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧩 Task Solving with Langchain Provided Tools as Functions</td>
<td align="left">🔍 Language Processing</td>
<td align="left">Leverages Langchain tools for task-solving within AutoGen.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_langchain.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">📚 RAG: Group Chat with Retrieval Augmented Generation</td>
<td align="left">🤝 Collaboration</td>
<td align="left">Enables group chat with Retrieval Augmented Generation (RAG) to support information sharing.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_groupchat_RAG" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">⚙️ Function Inception: Update/Remove Functions During Conversations</td>
<td align="left">🔧 Development Tools</td>
<td align="left">Allows AutoGen agents to modify their functions dynamically during conversations.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_inception_function.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🔊 Agent Chat with Whisper</td>
<td align="left">🎙️ Audio Processing</td>
<td align="left">Demonstrates AI agent capabilities for transcription and translation using Whisper.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_video_transcript_translate_with_whisper" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">📏 Constrained Responses via Guidance</td>
<td align="left">💡 Natural Language Processing</td>
<td align="left">Shows how to use guidance to constrain responses generated by agents.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_guidance.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🌍 Browse the Web with Agents</td>
<td align="left">🌐 Information Retrieval</td>
<td align="left">Explains how to configure agents to browse and retrieve information from the web.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_surfer.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">📊 SQL: Natural Language Text to SQL Query Using Spider Benchmark</td>
<td align="left">💾 Database Management</td>
<td align="left">Converts natural language inputs into SQL queries using the Spider benchmark.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_sql_spider.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🕸️ Web Scraping with Apify</td>
<td align="left">🌐 Data Gathering</td>
<td align="left">Illustrates web scraping techniques with Apify using AutoGen.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_webscraping_with_apify" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🕷️ Web Crawling: Crawl Entire Domain with Spider API</td>
<td align="left">🌐 Data Gathering</td>
<td align="left">Explains how to crawl entire domains using the Spider API.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_webcrawling_with_spider" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">💻 Write a Software App Task by Task with Specially Designed Functions</td>
<td align="left">💻 Software Development</td>
<td align="left">Builds a software application step-by-step using designed functions.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_function_call_code_writing.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<blockquote>
<p dir="auto"><strong>Human Development</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th align="left">Use Case</th>
<th align="left">Industry</th>
<th align="left">Description</th>
<th align="left">Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">💬 Simple Example in ChatGPT Style</td>
<td align="left">🧠 Conversational AI</td>
<td align="left">Demonstrates a simple conversational example in the style of ChatGPT.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/samples/simple_chat.py"><img src="https://camo.githubusercontent.com/4cf5b96c67c99c1a0875533c225c6c4ac2cf9d652fdaccaed12c5d0d75ddc797/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4578616d706c652d626c75653f6c6f676f3d6f70656e6169" alt="Example" data-canonical-src="https://img.shields.io/badge/View-Example-blue?logo=openai" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🤖 Auto Code Generation, Execution, Debugging and Human Feedback</td>
<td align="left">💻 Software Development</td>
<td align="left">Showcases code generation, execution, debugging with human feedback integrated into the workflow.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_human_feedback.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">👥 Automated Task Solving with GPT-4 + Multiple Human Users</td>
<td align="left">🤝 Collaboration</td>
<td align="left">Enables task solving with multiple human users collaborating with GPT-4.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_two_users.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🔄 Agent Chat with Async Human Inputs</td>
<td align="left">🧠 Conversational AI</td>
<td align="left">Supports asynchronous human input during agent conversations.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/Async_human_input.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<blockquote>
<p dir="auto"><strong>Agent Teaching and Learning</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th align="left">Use Case</th>
<th align="left">Industry</th>
<th align="left">Description</th>
<th align="left">Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">📘 Teach Agents New Skills &amp; Reuse via Automated Chat</td>
<td align="left">🎓 Education &amp; Training</td>
<td align="left">Demonstrates teaching new skills to agents and enabling their reuse in automated chats.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_teaching" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 Teach Agents New Facts, User Preferences and Skills Beyond Coding</td>
<td align="left">🎓 Education &amp; Training</td>
<td align="left">Shows how to teach agents new facts, user preferences, and non-coding skills.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_teachability" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🤖 Teach OpenAI Assistants Through GPTAssistantAgent</td>
<td align="left">💻 AI Assistant Development</td>
<td align="left">Illustrates how to enhance OpenAI assistants' capabilities using GPTAssistantAgent.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_teachable_oai_assistants.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🔄 Agent Optimizer: Train Agents in an Agentic Way</td>
<td align="left">🛠️ Optimization</td>
<td align="left">Explains how to train agents effectively in an agentic manner using the Agent Optimizer.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_agentoptimizer.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<blockquote>
<p dir="auto"><strong>Multi-Agent Chat with OpenAI Assistants in the loop</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th align="left">Use Case</th>
<th align="left">Industry</th>
<th align="left">Description</th>
<th align="left">Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">🌟 Hello-World Chat with OpenAI Assistant in AutoGen</td>
<td align="left">🤖 Conversational AI</td>
<td align="left">A basic example of chatting with OpenAI Assistant using AutoGen.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_oai_assistant_twoagents_basic.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🔧 Chat with OpenAI Assistant using Function Call</td>
<td align="left">🔧 Development Tools</td>
<td align="left">Illustrates how to use function calls with OpenAI Assistant in chats.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_oai_assistant_function_call.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 Chat with OpenAI Assistant with Code Interpreter</td>
<td align="left">💻 Software Development</td>
<td align="left">Demonstrates the use of OpenAI Assistant as a code interpreter in chats.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_oai_code_interpreter.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🔍 Chat with OpenAI Assistant with Retrieval Augmentation</td>
<td align="left">📚 Information Retrieval</td>
<td align="left">Enables retrieval-augmented conversations with OpenAI Assistant.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_oai_assistant_retrieval.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🤝 OpenAI Assistant in a Group Chat</td>
<td align="left">🤝 Collaboration</td>
<td align="left">Shows how OpenAI Assistant can collaborate with other agents in a group chat.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_oai_assistant_groupchat.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🛠️ GPTAssistantAgent based Multi-Agent Tool Use</td>
<td align="left">🔧 Development Tools</td>
<td align="left">Explains how to use GPTAssistantAgent for multi-agent tool usage.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/gpt_assistant_agent_function_call.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<blockquote>
<p dir="auto"><strong>Non-OpenAI Models</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th align="left">Use Case</th>
<th align="left">Industry</th>
<th align="left">Description</th>
<th align="left">Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">♟️ Conversational Chess using Non-OpenAI Models</td>
<td align="left">🎮 Gaming</td>
<td align="left">Explores conversational chess implemented with non-OpenAI models.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_nested_chats_chess_altmodels" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<blockquote>
<p dir="auto"><strong>Multimodal Agent</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th align="left">Use Case</th>
<th align="left">Industry</th>
<th align="left">Description</th>
<th align="left">Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">🎨 Multimodal Agent Chat with DALLE and GPT-4V</td>
<td align="left">🖼️ Multimedia AI</td>
<td align="left">Combines DALLE and GPT-4V for multimodal agent communication.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_dalle_and_gpt4v.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🖌️ Multimodal Agent Chat with Llava</td>
<td align="left">📷 Image Processing</td>
<td align="left">Uses Llava for enabling multimodal agent conversations with image processing.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_lmm_llava.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🖼️ Multimodal Agent Chat with GPT-4V</td>
<td align="left">🖼️ Multimedia AI</td>
<td align="left">Leverages GPT-4V for visual and conversational interactions in multimodal agents.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_lmm_gpt-4v.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<blockquote>
<p dir="auto"><strong>Long Context Handling</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th align="left">Use Case</th>
<th align="left">Industry</th>
<th align="left">Description</th>
<th align="left">Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">📜 Long Context Handling as A Capability</td>
<td align="left">🧠 AI Capability</td>
<td align="left">Demonstrates techniques for handling long context effectively within AI workflows.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/notebooks/agentchat_transform_messages" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<blockquote>
<p dir="auto"><strong>Evaluation and Assessment</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th align="left">Use Case</th>
<th align="left">Industry</th>
<th align="left">Description</th>
<th align="left">Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">📊 AgentEval: A Multi-Agent System for Assessing Utility of LLM-Powered Applications</td>
<td align="left">📈 Performance Evaluation</td>
<td align="left">Introduces AgentEval for evaluating and assessing the performance of LLM-based applications.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agenteval_cq_math.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<blockquote>
<p dir="auto"><strong>Automatic Agent Building</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th align="left">Use Case</th>
<th align="left">Industry</th>
<th align="left">Description</th>
<th align="left">Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">🏗️ Automatically Build Multi-agent System with AgentBuilder</td>
<td align="left">🤖 AI Development</td>
<td align="left">Explains how to automatically build multi-agent systems using the AgentBuilder tool.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/autobuild_basic.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">📚 Automatically Build Multi-agent System from Agent Library</td>
<td align="left">🤖 AI Development</td>
<td align="left">Shows how to construct multi-agent systems by leveraging a pre-defined agent library.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/autobuild_agent_library.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<blockquote>
<p dir="auto"><strong>Observability</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th align="left">Use Case</th>
<th align="left">Industry</th>
<th align="left">Description</th>
<th align="left">Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">📊 Track LLM Calls, Tool Usage, Actions and Errors using AgentOps</td>
<td align="left">📈 Monitoring &amp; Analytics</td>
<td align="left">Demonstrates how to monitor LLM interactions, tool usage, and errors using AgentOps.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_agentops.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<blockquote>
<p dir="auto"><strong>Enhanced Inferences</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th align="left">Use Case</th>
<th align="left">Industry</th>
<th align="left">Description</th>
<th align="left">Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">🔗 API Unification</td>
<td align="left">🔧 API Management</td>
<td align="left">Explains how to unify API usage with documentation and code examples.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/docs/Use-Cases/enhanced_inference/#api-unification" rel="nofollow"><img src="https://camo.githubusercontent.com/9274d655850ab2a3f78cb706faf43f0f1072570d69bb6d685c601015372b52d8/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d446f63756d656e746174696f6e2d626c75653f6c6f676f3d72656164746865646f6373" alt="Documentation" data-canonical-src="https://img.shields.io/badge/View-Documentation-blue?logo=readthedocs" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">⚙️ Utility Functions to Help Managing API Configurations Effectively</td>
<td align="left">🔧 API Management</td>
<td align="left">Demonstrates utility functions to manage API configurations more effectively.</td>
<td align="left"><a href="https://microsoft.github.io/autogen/0.2/docs/topics/llm_configuration" rel="nofollow"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">💰 Cost Calculation</td>
<td align="left">📈 Cost Management</td>
<td align="left">Introduces methods for tracking token usage and estimating costs for LLM interactions.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/agentchat_cost_token_tracking.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">⚡ Optimize for Code Generation</td>
<td align="left">📊 Optimization</td>
<td align="left">Highlights cost-effective optimization techniques for improving code generation with LLMs.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/oai_completion.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">📐 Optimize for Math</td>
<td align="left">📊 Optimization</td>
<td align="left">Explains techniques to optimize LLM performance for solving mathematical problems.</td>
<td align="left"><a href="https://github.com/microsoft/autogen/blob/0.2/notebook/oai_chatgpt_gpt4.ipynb"><img src="https://camo.githubusercontent.com/a55d89492b810e366db5724738da2d499d1fba6027ab28128dbc0354d32d6c03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f566965772d4e6f7465626f6f6b2d626c75653f6c6f676f3d6a757079746572" alt="Notebook" data-canonical-src="https://img.shields.io/badge/View-Notebook-blue?logo=jupyter" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><strong>Framework Name</strong>: <strong>Agno</strong></h3><a id="user-content-framework-name-agno" class="anchor" aria-label="Permalink: Framework Name: Agno" href="#framework-name-agno"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<blockquote>
<p dir="auto"><strong>UseCase</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th align="left">Use Case</th>
<th align="left">Industry</th>
<th align="left">Description</th>
<th align="left">Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">🤖 Support Agent</td>
<td align="left">💻 Software Development / AI / Framework Support</td>
<td align="left">The Agno Support Agent helps developers with the Agno framework by providing real-time answers, explanations, and code examples.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/agno_support_agent.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🎥 YouTube Agent</td>
<td align="left">📺 Media &amp; Content</td>
<td align="left">An intelligent agent that analyzes YouTube videos by generating detailed summaries, timestamps, themes, and content breakdowns using AI tools.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/youtube_agent.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">📊 Finance Agent</td>
<td align="left">💼 Finance</td>
<td align="left">An advanced AI-powered market analyst that delivers real-time stock market insights, analyst recommendations, financial deep-dives, and sector-specific trends. Supports prompts for detailed analysis of companies like AAPL, TSLA, NVDA, etc.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/thinking_finance_agent.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">📚 Study Partner</td>
<td align="left">🎓 Education</td>
<td align="left">Assists users in learning by finding resources, answering questions, and creating study plans.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/study_partner.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🛍️ Shopping Partner Agent</td>
<td align="left">🏬 E-commerce</td>
<td align="left">A product recommender agent that helps users find matching products based on preferences from trusted platforms like Amazon, Flipkart, etc.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/shopping_partner.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🎓 Research Scholar Agent</td>
<td align="left">🧠 Education / Research</td>
<td align="left">An AI-powered academic assistant that performs advanced academic searches, analyzes recent publications, synthesizes findings across disciplines, and writes well-structured academic reports with proper citations.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/research_agent_exa.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 Research Agent</td>
<td align="left">🗞️ Media &amp; Journalism</td>
<td align="left">A research agent that combines web search and professional journalistic writing. It performs deep investigations and produces NYT-style reports.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/research_agent.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🍳 Recipe Creator</td>
<td align="left">🍽️ Food &amp; Culinary</td>
<td align="left">An AI-powered recipe recommendation agent that provides personalized recipes based on ingredients, preferences, and time constraints.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/recipe_creator.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🗞️ Finance Agent</td>
<td align="left">💼 Finance</td>
<td align="left">A powerful financial analyst agent combining real-time stock data, analyst insights, company fundamentals, and market news. Ideal for analyzing companies like Apple, Tesla, NVIDIA, and sectors like semiconductors or automotive.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/finance_agent.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 Financial Reasoning Agent</td>
<td align="left">📈 Finance</td>
<td align="left">Uses a Claude-3.5 Sonnet-based agent to analyze stocks like NVDA using tools for reasoning and Yahoo Finance data.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/reasoning_finance_agent.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🤖 Readme Generator Agent</td>
<td align="left">💻 Software Dev</td>
<td align="left">Agent generates high-quality READMEs for GitHub repositories using repo metadata.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/readme_generator.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🎬 Movie Recommendation Agent</td>
<td align="left">🎥 Entertainment</td>
<td align="left">An intelligent agent that gives personalized movie recommendations using Exa and GPT-4o, analyzing genres, themes, and latest ratings.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/movie_recommedation.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🔍 Media Trend Analysis Agent</td>
<td align="left">📰 Media &amp; News</td>
<td align="left">Analyzes emerging trends, patterns, and influencers from digital platforms using AI-powered agents and scraping.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/media_trend_analysis_agent.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">⚖️ Legal Document Analysis Agent</td>
<td align="left">🏛️ Legal Tech</td>
<td align="left">An AI agent that analyzes legal documents from PDF URLs and provides legal insights based on a knowledge base using vector embeddings and GPT-4o.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/legal_consultant.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🤔 DeepKnowledge</td>
<td align="left">🧠 Research</td>
<td align="left">This agent performs iterative searches through its knowledge base, breaking down complex queries into sub-questions and synthesizing comprehensive answers. It uses Agno docs for demonstration and is designed for deep reasoning and exploration.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/deep_knowledge.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">📚 Book Recommendation Agent</td>
<td align="left">🧠 Publishing &amp; Media</td>
<td align="left">An intelligent agent that provides personalized book suggestions using literary data, reader preferences, reviews, and release info.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/book_recommendation.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🏠 MCP Airbnb Agent</td>
<td align="left">🛎️ Hospitality</td>
<td align="left">Create an AI Agent using MCP and Llama 4 to search Airbnb listings with filters like workspace &amp; transport proximity.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/airbnb_mcp.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🤖 Assist	 Agent</td>
<td align="left">🧠 AI Framework</td>
<td align="left">An AI agent using GPT-4o to answer questions about the Agno framework with hybrid search and embedded knowledge.</td>
<td align="left"><a href="https://github.com/agno-agi/agno/blob/main/cookbook/examples/agents/agno_assist.py"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><strong>Framework Name</strong>: <strong>Langgraph</strong></h3><a id="user-content-framework-name-langgraph" class="anchor" aria-label="Permalink: Framework Name: Langgraph" href="#framework-name-langgraph"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<blockquote>
<p dir="auto"><strong>UseCase</strong></p>
</blockquote>
<markdown-accessiblity-table><table>
<thead>
<tr>
<th align="left">Use Case</th>
<th align="left">Industry</th>
<th align="left">Description</th>
<th align="left">Notebook</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">🤖 Chatbot Simulation Evaluation</td>
<td align="left">💻 💬 AI / Quality Assurance</td>
<td align="left">Simulate user interactions to evaluate chatbot performance, ensuring robustness and reliability in real-world scenarios.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/chatbot-simulation-evaluation/agent-simulation-evaluation.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 Information Gathering via Prompting</td>
<td align="left">🧠 AI / Research &amp; Development</td>
<td align="left">This tutorial demonstrates how to design a LangGraph workflow that utilizes prompting techniques to gather information effectively. It showcases how to structure prompts and manage the flow of information to build intelligent agents.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/chatbots/information-gather-prompting.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 Code Assistant with LangGraph</td>
<td align="left">💻 Software Development</td>
<td align="left">This tutorial demonstrates how to build a resilient code assistant using LangGraph. It guides you through creating a graph-based agent that can handle code generation, error checking, and iterative refinement, ensuring robust and accurate coding assistance.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/code_assistant/langgraph_code_assistant.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧑‍💼 Customer Support Agent</td>
<td align="left">🧑‍💼 Customer Support Agent</td>
<td align="left">This tutorial demonstrates how to build a customer support agent using LangGraph. It guides you through creating a graph-based agent that can handle customer inquiries, providing automated support and enhancing user experience.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/customer-support/customer-support.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🔁 Extraction with Retries</td>
<td align="left">🧠 AI / Data Extraction</td>
<td align="left">This tutorial demonstrates how to implement retry mechanisms in LangGraph workflows, ensuring robust data extraction processes that can handle transient errors and improve reliability.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/extraction/retries.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 Multi-Agent Workflow</td>
<td align="left">🧠 AI / Workflow Orchestration</td>
<td align="left">This tutorial demonstrates how to build a multi-agent system using LangGraph's agent supervisor. It guides you through creating a supervisor agent that orchestrates multiple specialized agents, managing task delegation and communication flow.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/multi_agent/agent_supervisor.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 Hierarchical Agent Teams</td>
<td align="left">🧠 AI / Workflow Orchestration</td>
<td align="left">This tutorial demonstrates how to build a hierarchical agent system using LangGraph. It guides you through creating a top-level supervisor agent that delegates tasks to specialized sub-agents, enabling complex workflows with clear task delegation and communication.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/multi_agent/hierarchical_agent_teams.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🤝 Multi-Agent Collaboration</td>
<td align="left">🧠 AI / Workflow Orchestration</td>
<td align="left">This tutorial demonstrates how to implement multi-agent collaboration using LangGraph. It guides you through creating multiple specialized agents that work together to accomplish a complex task, showcasing the power of agent collaboration in AI workflows.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/multi_agent/multi-agent-collaboration.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 Plan-and-Execute Agent</td>
<td align="left">🧠 AI / Workflow Orchestration</td>
<td align="left">This tutorial demonstrates how to build a "Plan-and-Execute" style agent using LangGraph. It guides you through creating an agent that first generates a multi-step plan and then executes each step sequentially, revisiting and modifying the plan as necessary. This approach is inspired by the Plan-and-Solve paper and the Baby-AGI project, aiming to enhance long-term planning and task execution in AI workflows.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/plan-and-execute/plan-and-execute.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 SQL Agent</td>
<td align="left">🧠 AI / Database Interaction</td>
<td align="left">This tutorial demonstrates how to build an agent that can answer questions about a SQL database. The agent fetches available tables, determines relevance to the question, retrieves schemas, generates a query, checks for errors, executes it, and formulates a response.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/sql-agent.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 Reflection Agent</td>
<td align="left">🧠 AI / Workflow Orchestration</td>
<td align="left">This tutorial demonstrates how to build a reflection agent using LangGraph. It guides you through creating an agent that can critique and revise its own outputs, enhancing the quality and reliability of generated content.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/reflection/reflection.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 Reflexion Agent</td>
<td align="left">🧠 AI / Workflow Orchestration</td>
<td align="left">This tutorial demonstrates how to build a reflexion agent using LangGraph. It guides you through creating an agent that can reflect on its actions and outcomes, enabling iterative improvement and more accurate decision-making in complex workflows.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/reflexion/reflexion.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left"><strong>LangGraph Agentic RAG</strong></td>
<td align="left"></td>
<td align="left"></td>
<td align="left"></td>
</tr>
<tr>
<td align="left">🧠 <strong>Adaptive RAG</strong></td>
<td align="left">🧠 AI / Information Retrieval</td>
<td align="left">This tutorial demonstrates how to build an Adaptive RAG system using LangGraph. It guides you through creating a dynamic retrieval process that adjusts based on query complexity, enhancing the efficiency and accuracy of information retrieval.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/rag/langgraph_adaptive_rag.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 <strong>Adaptive RAG (Local)</strong></td>
<td align="left">🧠 AI / Information Retrieval</td>
<td align="left">This tutorial focuses on implementing Adaptive RAG with local models, allowing for offline retrieval and generation, which is crucial for environments with limited internet access or privacy concerns.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/rag/langgraph_adaptive_rag_local.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🤖 <strong>Agentic RAG</strong></td>
<td align="left">🤖 AI / Intelligent Agents</td>
<td align="left">Learn to build an Agentic RAG system where an agent determines the best retrieval strategy before generating a response, improving the relevance and accuracy of answers.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/rag/langgraph_agentic_rag.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🤖 <strong>Agentic RAG (Local)</strong></td>
<td align="left">🤖 AI / Intelligent Agents</td>
<td align="left">This tutorial extends Agentic RAG to local environments, enabling the use of local models and data sources for retrieval and generation tasks.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/rag/langgraph_agentic_rag_local.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 <strong>Corrective RAG (CRAG)</strong></td>
<td align="left">🧠 AI / Information Retrieval</td>
<td align="left">Implement a Corrective RAG system that evaluates and refines retrieved documents before passing them to the generator, ensuring higher-quality outputs.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/rag/langgraph_crag.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 <strong>Corrective RAG (Local)</strong></td>
<td align="left">🧠 AI / Information Retrieval</td>
<td align="left">This tutorial focuses on building a Corrective RAG system using local resources, allowing for offline document evaluation and refinement processes.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/rag/langgraph_crag_local.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 <strong>Self-RAG</strong></td>
<td align="left">🧠 AI / Information Retrieval</td>
<td align="left">Learn to implement Self-RAG, where the system reflects on its responses and retrieves additional information if necessary, enhancing the accuracy and relevance of generated content.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/rag/langgraph_self_rag.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
<tr>
<td align="left">🧠 <strong>Self-RAG (Local)</strong></td>
<td align="left">🧠 AI / Information Retrieval</td>
<td align="left">This tutorial demonstrates how to implement Self-RAG using local models and data sources, enabling offline reflection and retrieval processes.</td>
<td align="left"><a href="https://github.com/langchain-ai/langgraph/blob/main/docs/docs/tutorials/rag/langgraph_self_rag_local.ipynb"><img src="https://camo.githubusercontent.com/dedc16edc737919ee0c0c949103694d595b266949f1dd423d7d8ff97fa5c1fb3/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d41492b4167656e742b436f6465266d6573736167653d507974686f6e26636f6c6f723d253233323434636431" alt="AI Agent Code - Python" data-canonical-src="https://img.shields.io/static/v1?label=AI+Agent+Code&amp;message=Python&amp;color=%23244cd1" style="max-width: 100%;"></a></td>
</tr>
</tbody>
</table></markdown-accessiblity-table>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">🤝 Contributing</h2><a id="user-content--contributing" class="anchor" aria-label="Permalink: 🤝 Contributing" href="#-contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">Contributions are welcome! 🎉 Here's how you can help:</p>
<ol dir="auto">
<li>Fork the repository.</li>
<li>Add a new use case or improve an existing one.</li>
<li>Submit a pull request with your changes.</li>
</ol>
<p dir="auto">Please follow our <a href="/ashishpatel26/500-AI-Agents-Projects/blob/main/CONTRIBUTING.md">Contributing Guidelines</a> for more details.</p>
<hr>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto">📜 License</h2><a id="user-content--license" class="anchor" aria-label="Permalink: 📜 License" href="#-license"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto">This repository is licensed under the MIT License. See the <a href="/ashishpatel26/500-AI-Agents-Projects/blob/main/LICENSE">LICENSE</a> file for more information.</p>
<hr>
