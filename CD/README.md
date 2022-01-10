# CD<br>
Conceitos<br>

**Pipeline de Deploy**<br>
<kbd>
    <img src="https://github.com/fabiokerber/CI_CD/blob/main/img/100120220920.JPG">
</kbd>
<br />
<br />

**Colaboração**<br>
Todos colaborando com o mesmo objetivo!<br>
<kbd>
    <img src="https://github.com/fabiokerber/CI_CD/blob/main/img/100120220925.JPG">
</kbd>
<br />
<br />

**Etapas de Deploy**<br>
**Release Antipatterns = Bad trip!!**<br>
&nbsp;&nbsp;&nbsp;&nbsp;Gerenciamento manual de ambientes > Sempre garantir que os testes sejam realizados nos ambientes de forma correta (Homologação deve estar igual à Produção, garantindo assim que funcionará corretamente em Produção).<br>
&nbsp;&nbsp;&nbsp;&nbsp;- **Resultado:** Deploy não confiável.<br>
&nbsp;&nbsp;&nbsp;&nbsp;- **Regra:** Todos os ambientes são tratados como código, versionado e criados de maneira *automatizada*.<br>
</br>
&nbsp;&nbsp;&nbsp;&nbsp;Dev nunca viu Ops?<br>
&nbsp;&nbsp;&nbsp;&nbsp;Deploys longos? Horas ou dias?<br>
&nbsp;&nbsp;&nbsp;&nbsp;Rollbacks frequentes?<br>
&nbsp;&nbsp;&nbsp;&nbsp;-  **Resultado:** Deploy lento, propício ao erro, não confiável.<br>
&nbsp;&nbsp;&nbsp;&nbsp;-  **Regra:** Somente duas tarefas devem ser executadas manualmente:<br> 
&nbsp;&nbsp;&nbsp;&nbsp;1) Escolher a Release.<br> 
&nbsp;&nbsp;&nbsp;&nbsp;2) Qualquer um pode clicar no "Deploy Button", pois todo o deploy está "codado" e automatizado.<br>
</br>
&nbsp;&nbsp;&nbsp;&nbsp;Deploy apenas no *fim do ciclo* de desenvolvimento(não é certeza de que o deploy será realizado com sucesso em produção).<br>
&nbsp;&nbsp;&nbsp;&nbsp;- **Resultado:** Pouca colaboração, problemas só aparecem no dia da publicação, não confiável e nem rápido, *"achismo"*.<br>
&nbsp;&nbsp;&nbsp;&nbsp;- **Regra:** Deploy faz parte do desenvolvimento desde a primeira interação, todos definem um *delivery team*.<br>
<kbd>
    <img src="https://github.com/fabiokerber/CI_CD/blob/main/img/100120220928.JPG">
</kbd>
<br />
<br />

**Entrega Contínua vs Deploy Contínuo**<br>
<kbd>
    <img src="https://github.com/fabiokerber/CI_CD/blob/main/img/100120221002.JPG">
</kbd>
<br />
<br />

**Antes de começar com CD**<br>
Master com Build OK podendo ser deployado a qualquer momento.<br>
Testes sempre sendo realizados.<br>
Ambientes sempre deployáveis em qualquer ambiente e em código!.<br>
<kbd>
    <img src="https://github.com/fabiokerber/CI_CD/blob/main/img/100120221041.JPG">
</kbd>
<br />
<br />