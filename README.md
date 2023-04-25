# Teste desenveolvedor Frontend Angularjs

## Objetivo

O objetivo do teste é verificar a capacidade do candidato de resolver problemas, desenvolver melhorias e aprimorar o código. A aplicação possui bugs para serem resolvidos e o código possui muitas opções de melhoria.

### Bugs a serem resolvidos

- O botão de adicionar não está funcionando;
- A edição dos elementos não está funcionando;
- Ao clicar em 'SAVE REPORT' a aplicação está sendo encerrada, porém o report é salvo.

### Melhorias

O código tem muito espaço para melhorias, como criação de componentes, arquitetura, etc. Fique a vontade para realizar melhorias.

Inicialização:

```
npm install
grunt build
npm start
```

Após realizar as edições execute novamente o `grunt build` e o `npm start`

**FEATURES**

    After pressing the START button:
    	Disables start button
    	Enables stop button
    	Starts updating the chart and data.

    After pressing the STOP button:
    	Enables start button
    	Disables stop button
    	Stops updating the chart and data.

    After pressing the CLEAR button:
    	Clears the chart and all data.

    After pressing the SAVE REPORT button:
    	Exports data report in a text file.

    After pressing a sequence bar:
    	Opens the Edit sequence dialog.

    After pressing the + button:
    	Opens the Create sequence dialog.

    After pressing the OK button in the Edit/Create dialog:
    	Validates the data.
    	If not OK shows notice about data format.

    	If OK:
    	Updates the sequence list.
    	Closes the dialog.

    After pressing the Delete button in the Edit dialog:
    	Deletes sequence from sequence list.
    	Closes the dialog.


    **Additional demonstration only feature**
    In the Edit/Create dialog after clicking checkbox, one can edit the randomness probability (weights) for each of the nucleotide in the generator.

Copyright 2015 Marcin Wolniewicz.

Licensed under GNU GPL v3
