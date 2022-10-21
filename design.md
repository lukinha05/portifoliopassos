## 1° Trimestre atividades

### Atividade academia senai 
https://www.figma.com/file/OxJqgGBW2X1A4lB8RgJoHD/Senai-Gym

### Prova design 
https://www.figma.com/file/ErIVYlya1lExDESaDFMcjT/Untitled

## 2° Trimestre atividades
### Atividade Lógica Booleana aplicada em Listas
private void btnRmvActionPerformed(java.awt.event.ActionEvent evt) {                                       
        String elemento = campoItem.getText();//Obter Texto
        if(verificaSeExiste(elemento) == false){
            JOptionPane.showMessageDialog(this,"Este item não existe!");
        }
        else{
            lista.remove(elemento);// adicionar na lista
            campoItem.setText(null);//Limpar o campo de texto
            exibeLista();
        }
    }

