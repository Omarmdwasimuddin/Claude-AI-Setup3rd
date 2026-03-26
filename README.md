## Claude AI Setup From 3rd parties

#### visit- https://ollama.com/ 

![ollama](/public/Img/ollama.png)

#### copy prompt-
```
irm https://ollama.com/install.ps1 | iex
```
#### powershell e install koro
![](/public/Img/powershell.png)

#### click model
![](/public/Img/click-Models.png)

#### search- gpt-oss and click gpt-oss
![](/public/Img/gpt-oss.png)

#### models copy koro-
![](/public/Img/models.png)

#### powershell e paste koro-
```
ollama pull gpt-oss:20b
```

#### powershell e check koro-
```
ollama --version
```

#### click Claude Code
![](/public/Img/clickClaudeCode.png)

#### powershell e install koro (windows)
```
irm https://claude.ai/install.ps1 | iex
```

#### powershell e check koro-
```
claude --version
```

#### copy koro-
![](/public/Img/quicksetup.png)

#### powershell e daw-
```
ollama launch claude --model gpt-oss:20b
```
#### click Enter for next steps
![](/public/Img/1st.png)
![](/public/Img/3rd.png)

#### Note: gpt-oss:20b er jonno RAM lagbe 13.2GB na hole run korbe na error ashbe. ar gpt-oss:20b er bikolpo holo(2GB RAM er) -
```
ollama pull llama3.2:3b
ollama launch claude --model llama3.2:3b
```