# CI<br>
Conceitos<br>

**Problema - Poucos momentos de integração**<br>
Risco maior ao "commitar" muitas alterações de uma única vez.<br>
<img src="https://github.com/fabiokerber/CI_CD/blob/main/img/030120221105.png" style="border:5px solid black">
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
<img src="https://github.com/fabiokerber/CI_CD/blob/main/img/030120221157.JPG">
<br />
<br />

**Gitlab Flow**<br>
<kbd>
    <img src="https://github.com/fabiokerber/CI_CD/blob/main/img/030120221200.JPG">
</kbd>
<br />
<br />

**Feature Flag**<br>
*Feature Flag* - O código é inserido no master, mas ele não é visível para a equipe. O Feature flag serve também para testar funcionalidades, por exemplo.<br>
<img src="https://github.com/fabiokerber/CI_CD/blob/main/img/030120221308.JPG">
<br />
<br />

**Merge vs Rebase**<br>
*Rebase* - "Merge" estado atual do Master para a branch que desejar. Develop atualizada com código da Master.<br>
<img src="https://github.com/fabiokerber/CI_CD/blob/main/img/030120221319.JPG">
<br />
<br />

**TTD**<br>
*TDD (Test Drive Development)* - Os testes em integração contínua são sobre feedback do software, como a maioria dos métodos ágeis.<br>
<img src="https://github.com/fabiokerber/CI_CD/blob/main/img/030120221329.JPG">
<br />
<br />

**Testes Automatizados**<br>
Existem diversas categorias e níveis de testes automatizados, aqui descaremos três: *unit tests*, *integration tests* e *functional tests*.<br>
- Os *unit tests* verificam unidades, como métodos e funções dentro do software. São os testes mais rápidos, baratos de escrever e sua manutenção é simples.<br>
- Os *testes de integração* são de um nível mais alto, e testam a relação de elementos, como por exemplo um banco de dados e o software. A realização destes testes é mais lenta, afinal possuem um outro grau de complexidade.<br>
- Testes de um nível ainda maior, são os *functional tests*, que testam o sistema completo e garante a correção de funcionalidades no ponto de vista do cliente.<br>
<img src="https://github.com/fabiokerber/CI_CD/blob/main/img/030120221331.JPG">
<br />
<br />

