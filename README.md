# Exportação automática de Projetos 🏗️

Esse repositório é uma adaptação de outro [repositório](https://github.com/abarichello/godot-ci).

A ideia principal aqui é que esse código sirva para que eu consiga automatizar a exportação de projetos de Godot e além disso aprender um pouco sobre github action e ci/cd.

# Como usar ?

1. Copie o arquivo [godot-ci](https://github.com/4RandomProgrammer/TestGodotAutomaticBuild/blob/main/.github/workflows/godot-ci.yml) para o seu repositório. É necessário que ele esteja dentro da pasta .github/workflow, pois se isso não acontecer ele não irá reconhecer automaticamente a ação no github actions.
2. Para esse repositório, é necessário você criar um token de acesso para a ação funcionar automaticamente. Tutorial pode ser encontrado [aqui](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-personal-access-token-classic). Observação: você pode 
3. Para essa versão é necessário exportar com o PCK embutido. Ao criar opções de exportação lembre-se de marcar essa opção. Caso não deseje lidar com nada disso, só copiar o arquivo: [export_presets.cfg](https://github.com/4RandomProgrammer/TestGodotAutomaticBuild/blob/main/base/project.godot) para o seu repositório, colocando ele na mesma pasta do project.godot.
4. Clicar no menu actions e botar a ação godot-ci para rodar.
5. Ao terminar de rodar, você pode ver que ela terá uma versão de release em seu repositório. Agora você pode baixar e jogar.