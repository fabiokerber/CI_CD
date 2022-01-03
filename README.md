# CI_CD<br>
Conceitos<br>

**Problema - Poucos momentos de integração**<br>
Risco maior ao "commitar" muitas alterações de uma única vez.<br>
<img src="https://github.com/fabiokerber/CI_CD/blob/main/img/030120221105.png">
<br />
<br />

**Integrações frequentes contínuas**<br>
Entregas frequentes e com menor criticidadade.<br>
<img src="https://github.com/fabiokerber/CI_CD/blob/main/img/030120221107.png">
<br />
<br />

**Multi-Repo vs Mono-Repo**<br>
Mono-Repo - Único repositório, refatoração melhor, porém controle e organização mais complexa.<br>
<img src="https://github.com/fabiokerber/CI_CD/blob/main/img/030120221111.png">
<br />
<br />

**Boas práticas**<br>
<img src="https://github.com/fabiokerber/CI_CD/blob/main/img/030120221119.jpg">
<br />
<br />

**Comparando Branches**<br>
- *Temporários (branches locais)* - São branches localizados apenas na máquina local e deverão se extiguir, são utilizados para organizar fluxos de trabalho e depois realizar o commit.<br>
- *Feature Branches* - São utilizados para implementar funcionalidades ou orientar tarefas.<br>
- *Historical Branches (master e develop)* - As alterações ficam organizadas em commits baseados na cronologia no caso de um projeto de software.<br>
- *Environment Branches (Staging e Production)* - Existem branches que são baseados no ambiente, isto é, em que espaço é realizado o deploy.<br>
- *Maintenance Branches (Release e Hotfix)* - Temos, ainda, os branches de manutenção do sistema.<br>
- "Trunk-Based Development is a branching model that reduces this distance (between branches) to the minimum."<br>
<img src="https://github.com/fabiokerber/CI_CD/blob/main/img/030120221135.jpg">
<br />
<br />

**Github Flow**<br>
<img src="https://github.com/fabiokerber/CI_CD/blob/main/img/030120221157.jpg">
<br />
<br />

**Gitlab Flow**<br>
<img src="https://github.com/fabiokerber/CI_CD/blob/main/img/030120221200.jpg">
<br />
<br />