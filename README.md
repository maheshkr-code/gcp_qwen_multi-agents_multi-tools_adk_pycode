### gcp_qwen_multiagents_multitools_adk_pycode

Run $ ollama ps, list, serve to make sure the Qwen9B has been pulled and successfully served locally

```
root@MikkyBoy:/mnt/d/qwen_multiagents_multitools_adk_python# ollama list
NAME          ID              SIZE      MODIFIED
qwen3.5:9b    6488c96fa5fa    6.6 GB    2 weeks ago
```

```
python3 -m venv .venv
source .venv/bin/activate
pip install google-adk
adk create currencyagent
adk run currencyagent
adk web currencyagent
```

<img width="1918" height="1017" alt="Screenshot 2026-07-28 221106" src="https://github.com/user-attachments/assets/1e9fafce-62af-48c4-a9c1-241689f6f1dc" />
<img width="1882" height="1101" alt="Screenshot 2026-07-28 221042" src="https://github.com/user-attachments/assets/f3e55d00-23f8-4564-9509-a0d33ca83b5a" />
<img width="707" height="367" alt="Screenshot 2026-08-16 230046" src="https://github.com/user-attachments/assets/c2c4c4de-a44d-4868-8eaf-1440bbd1fe37" />
<img width="1190" height="730" alt="Screenshot 2026-08-16 230034" src="https://github.com/user-attachments/assets/e60e61e8-8293-4c5b-bde8-6030153b314a" />
<img width="1502" height="781" alt="Screenshot 2026-08-16 230011" src="https://github.com/user-attachments/assets/97c0bed1-cab5-41f5-b6fc-407e098e2839" />
<img width="1887" height="1032" alt="Screenshot 2026-08-16 225826" src="https://github.com/user-attachments/assets/3c3daa32-4fce-46a3-8c15-dd90caa99a8b" />
<img width="1897" height="1037" alt="Screenshot 2026-08-16 225208" src="https://github.com/user-attachments/assets/9f4906be-56de-4c3f-8b4c-a6c1eaca6795" />
<img width="1868" height="1026" alt="Screenshot 2026-07-28 221208" src="https://github.com/user-attachments/assets/211517bf-d86b-4f8a-a763-9e2a484e4be6" />
