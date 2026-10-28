<h1 align="center">Guilherme Filardi</h1>

<p align="center">
  Engenharia Elétrica · UNESP Ilha Solteira<br>
  Embarcados · Controle · Confiabilidade · Software e dados
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/guilhermefilardifeis"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:guifilardi@gmail.com"><img src="https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"></a>
</p>

<p align="center">
  <img src="grovyle.jpeg" alt="Regret is proof you've grown. The fact that you wish you had done better means you are already someone who would." width="450">
</p>

---

### Quem sou

Sou eletricista de formação e acabo escrevendo bastante software. Gosto de problema que dá para medir: o número antes, o número depois e o motivo da diferença.

- **Eldorado Brasil**, Engenharia Industrial: planejamento e controle de projetos de CAPEX.
- **Zebra Aerodesign**, mais de 5 anos: Gerente de Projetos Elétricos e Safety Assessment e, antes, Gerente de Telemetria e Sistemas Embarcados.
- **UNESP Ilha Solteira**: reconhecimento de mérito como melhor aluno da turma e bolsa de iniciação científica do CNPq, com artigo aceito.
- **Confiabilidade**: FMEA, FTA, modelagem de ameaças e safety case, usados tanto em avião de competição (SAE ARP4761) quanto em software e dado corporativo.

### Projetos

**Engenharia e embarcados**

| Projeto | O que é | O número |
|---|---|---|
| **[Controle de potência para AeroDesign](https://github.com/Guilherme-Filardi/controle-potencia-aerodesign)** | Meu trabalho de graduação. Um ESP32 entre o receptor e o ESC mantém a mesma potência para a mesma posição do manche, mesmo com a bateria descarregando. Controle PID com ação antecipatória, modelo do motor levantado em bancada e placa feita em casa. | Sem controle, a potência caiu de 858 W para 641 W em 78 s. O modelo erra 18,8 W em dados que não entraram no ajuste; o modelo linear usual erra 41,2 W. |
| **Meu Civic G8** | Datalogger com ESP32 que lê a rede do carro pela porta OBD-II e manda os dados por Bluetooth para um aplicativo Android próprio. | |
| **Bancada pino sobre disco** | Instrumentação de baixo custo para ensaio de atrito. | Montada por R$ 600. Artigo aceito na revista RECRIAI em 2026. |

**Software e dados**

| Projeto | O que é | O número |
|---|---|---|
| **PAPEL** | Plataforma web interna de planejamento de projetos industriais na Eldorado Brasil. Python, PostgreSQL, API própria e tela em React. A arquitetura passou por safety assessment para não perder dado nem ficar fora do ar. | Mais de 50 projetos por ano e mais de 2.000 testes automatizados. |
| **[Análise Ethereum](https://github.com/Guilherme-Filardi/analise-ethereum)** | Estudo do ETH com dado público, de 2017 a 2026: risco de compra, gás por hora, previsão diária conferida no dia seguinte e um site para ver tudo. Python, FastAPI e React. | A faixa de 80% acertou 80,3% dos dias. A direção (sobe ou cai) acertou 51,7%, que é cara ou coroa: o tamanho do movimento é previsível, a direção não. |
| **Extrator de eventos corporativos** *(repositório privado)* | Lê avisos aos acionistas em PDF com o Claude e devolve 23 campos prontos para cadastro. Cada valor vem com o trecho do PDF que o prova, e regras em Python decidem o que vai para revisão humana. | 8 documentos e 184 campos, com gabarito para medir o acerto. 25 testes rodando no GitHub a cada envio. |

### Ferramentas

**Embarcados e hardware**<br>
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square)
![Simulink](https://img.shields.io/badge/Simulink-0076A8?style=flat-square)

**Software e dados**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-663399?style=flat-square&logo=css&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude%20API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Excel VBA](https://img.shields.io/badge/Excel%20VBA-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

**O que sei fazer, em palavras**

- **Elétrica e eletrônica:** projeto elétrico, eletrônica analógica e digital, processamento de sinais, máquinas e acionamentos.
- **Controle e embarcados:** PID com ação antecipatória, instrumentação, telemetria e aquisição de dados, protocolos I2C, MQTT, SBUS e S.Port.
- **Confiabilidade:** safety assessment e safety case, FMEA, FTA, modelagem de ameaças, análise de impacto no negócio (RTO e RPO).
- **Software:** Clean Architecture e DDD, API, testes automatizados, análise de dados e estatística.
- **Gestão:** projetos de CAPEX, controle físico-financeiro, liderança técnica de equipe. Inglês fluente.

---

### Tocando agora

<p align="center">
  <a href="https://open.spotify.com/user/12159242833"><img src="https://spotify-github-profile.kittinanx.com/api/view?uid=12159242833&cover_image=true&theme=default&show_offline=false&background_color=121212&interchange=false&profanity=false&hide_remaster=true" alt="Tocando agora no Spotify"></a>
</p>

<br>

> *I am not a good man*  
> *and maybe i'll never be*  
>   
> *but the sky knows*  
> *that i try my harder*  
> *to be better in every way.*  
>   
> *that despite my sins*  
> *and my lowest ways*  
>   
> *i try to be a better man*  
> *than the one i was yesterday.*
