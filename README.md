# Flavors

- Criar um novo Projeto: 

```sh
> flutter create -i swift -a kotlin app
```
ou 
```
> flutter create -i swift -a kotlin --org br.com.thyagoluciano app
```

- Opcional Configurar Firebase
    - Você pode seguir as intruções detalhadas de como configurar o firebase no seu projeto aqui: [Configuração do Firebase](https://firebase.google.com/docs/flutter/setup)
    - Você pode ver como configurar multiprojetos do firebase aqui: [Configurar vários projetos](https://firebase.google.com/docs/projects/multiprojects)

    Exemplo de estrutura de diretorio android:
    ```
    .
    ├── .gitignore
    ├── app
    │   ├── build.gradle
    │   └── src
    │       ├── debug
    │       │   └── AndroidManifest.xml
    │       ├── dev
    │       │   └── google-services.json
    ```

- Configuração Flavor Android [Step 2 Configurar Firebase + Flavor Android](https://github.com/thyagoluciano/flutter-boilerplate/commit/ac850a48b7218a702e2dc7d5dc8633448f585072)