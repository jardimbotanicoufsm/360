# Visão 360º

O repositório tem o intuito de hospedar uma página onde possam
ser visualizadas fotos esféricas utilizando o giroscópio/sensor de rotação do celular.

*Link de acesso:* [https://jbsm.inf.ufsm.br/360/](https://jbsm.inf.ufsm.br/360/)

> O site **não** irá funcionar corretamente em dispositivos sem sensor de rotação(desktops, notebooks)

> O site **não** funciona no navegador Brave em dispositivos móveis

## Como Usar

Para adicionar mais fotos é necessário editar o arquivo `panoramas.json` com o nome amigável (é mostrado na interface final) e a URI que aponta para a imagem final. Pode ser hospedada na própria página ou um site separado.

> **Aviso:** Hospedagem fora do Github Pages não foi testada.

A estrutura de cada item no `panoramas.json` é assim:
```json
{
    // nome User-Friendly do panorama que irá aparecer na interface do usuário
    "name": "Área 1", 
    // url que aponta para a imagem do panorama
    "path": "skyboxes/area-1.png", 
    // define se este panorama deve ser mostrado na interface
    "enabled": true 
}
```

Para criar as fotos panorâmicas, foi utilizado:
* Celular com câmera
* Tripé com ajuste fino de rotação
* Software `Kolor Autopano Giga`

