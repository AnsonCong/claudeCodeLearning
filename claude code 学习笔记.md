# Claude code 学习笔记

## opencode

官方配置站
<https://opencode.ai/docs/config/>

中文配置站
<https://www.opencodecn.com/docs/config>

实践opencode配置
<https://linux.do/t/topic/1430711>

默认配置文件位置：
Data: ~/.local/share/opencode
Cache: ~/.cache/opencode
Config: ~/.config/opencode
State: ~/.local/state/opencode

oh my open code插件
<https://github.com/code-yeongyu/oh-my-opencode>

opencode中文教程（全）
<https://learnopencode.com/1-start/>

opencode接入自定义中转站
<https://linux.do/t/topic/1329050>

## skills

概念讲解：<https://www.youtube.com/watch?v=yDc0_8emz7M>

skill社区： <https://56q4zfganj4cy.ok.kimi.link>

skill实战案例 <https://github.com/obra/superpowers/tree/main/skills>

【25% → 90%！别让 Skills 吃灰：Hooks + Commands + Agents 协同激活 AI 全部能力：Claude Code 工程化实践-哔哩哔哩】
 <https://b23.tv/GCEWg0G>
<https://blog.csdn.net/leoisaking/article/details/156203326>
<https://ruoyi.plus/practices/engineering/claude-code-hooks.html>

## claude code

GAC 平台：<https://gaccode.com/signup?ref=UWDADYQI>
宝玉老师的博文转录：<https://baoyu.io/blog/claude-code-boris-9-practical-tips-simple-config>
Ralph Wiggum 插件：<https://github.com/anthropics/claude-plugins-official/tree/main/plugins/ralph-wiggum>
【🚀Claude Code之父Boris分享终极使用技巧：Opus 4.5计划模式+iTerm2多Tab+自定义斜杠命令+GitHub Actions，效率倍增-哔哩哔哩】 <https://b23.tv/HpWhtVF>

Claude Agent SDK <https://www.youtube.com/watch?v=u1uyXXl_6N8>

<https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents>

## 其他

终端如何设置代理
<https://www.itfanr.cc/2021/07/15/setting-up-proxy-for-iterm-terminal-on-macos/>

minimax: sk-cp-qWXO1pBOqcWr-7TvjgIr4JRTIH6rBTj1kqmQy4MNsVrCwbYBzzxLwvrsjUMsX2A3BN1pz8-HLvJf8FejZjIwGZIof1EQkgR2ayR_pfQNzb4feUpNF_SMusI

glm4.7的key： c4a4ea46ce2c46fc9dc9746a7df6cb6f.4foyvZhf03kW6Nxb

verex AI：AQ.Ab8RN6K975qWqcgT6P4_VmeF0bpTT80XW1TtgHsmn-K3huUqdw

curl -X POST -H "Content-Type: application/json" "https://aiplatform.googleapis.com/v1/publishers/google/models/gemini-3-pro-preview:generateContent?key=AQ.Ab8RN6K975qWqcgT6P4_VmeF0bpTT80XW1TtgHsmn-K3huUqdw" -d '{"contents":{"role":"user","parts":[{"text":"Explain how AI works in a few words"}]}}'