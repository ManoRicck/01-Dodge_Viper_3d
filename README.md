https://github.com/user-attachments/assets/31aeb326-ac7b-4ce4-991a-52bd0bb848e9



<style>
  .center { text-align: center; }
  .badges { margin: 20px 0; }
  .feature-table, .tech-table { 
    width: 100%;
    border-collapse: collapse;
    margin: 20px 0;
  }
  .feature-table td, .tech-table td {
    padding: 12px;
    border: 1px solid #ddd;
    text-align: left;
  }
  .tech-table img { 
    width: 20px;
    vertical-align: middle;
    margin-right: 8px;
  }
  .code-block {
    background: #f4f4f4;
    padding: 15px;
    border-radius: 5px;
    overflow-x: auto;
    margin: 15px 0;
  }
  .file-structure {
    font-family: monospace;
    background: #282c34;
    color: #abb2bf;
    padding: 15px;
    border-radius: 5px;
    margin: 15px 0;
  }
  .footer {
    margin-top: 30px;
    padding-top: 20px;
    border-top: 1px solid #eee;
    text-align: center;
  }
</style>

<div class="center">
  <div class="badges">
    <img src="https://img.shields.io/badge/Blender-3D-orange?logo=blender" alt="Blender 3D">
    <img src="https://img.shields.io/badge/Three.js-WebGL-blue?logo=three.js" alt="Three.js">
    <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
    <img src="https://img.shields.io/badge/interactive-true-brightgreen" alt="Interactive">
  </div>

  <img width="90%" src="https://raw.githubusercontent.com/ManoRicck/01-Dodge_Viper_3d/main/preview.jpg" alt="Dodge Viper 3D Model">
</div>

## ✨ Demonstração ao Vivo
▶️ **[Clique para ver o modelo 3D em ação](https://manoricck.github.io/01-Dodge_Viper_3d/)**

## 🛠 Tecnologias Utilizadas

<table class="tech-table">
  <tr>
    <th>Tecnologia</th>
    <th>Uso no Projeto</th>
    <th>Documentação</th>
  </tr>
  <tr>
    <td><img src="https://cdn-icons-png.flaticon.com/512/561/561094.png"> <strong>Blender</strong></td>
    <td>Modelagem 3D do veículo</td>
    <td><a href="https://docs.blender.org/">Blender Docs</a></td>
  </tr>
  <tr>
    <td><img src="https://threejs.org/files/favicon.ico"> <strong>Three.js</strong></td>
    <td>Renderização Web 3D</td>
    <td><a href="https://threejs.org/docs/">Three.js Docs</a></td>
  </tr>
  <tr>
    <td><img src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png"> <strong>JavaScript</strong></td>
    <td>Controles interativos</td>
    <td><a href="https://developer.mozilla.org/pt-BR/docs/Web/JavaScript">MDN JavaScript</a></td>
  </tr>
  <tr>
    <td><img src="https://www.w3.org/html/logo/downloads/HTML5_Badge_256.png"> <strong>HTML5</strong></td>
    <td>Estrutura da página</td>
    <td><a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML">HTML5 Reference</a></td>
  </tr>
</table>

## 🎮 Controles Interativos
- 🖱️ **Rotação**: Arraste com o mouse para girar o modelo
- 🔍 **Zoom**: Use o scroll do mouse para aproximar/afastar
- ✋ **Panorâmica**: Segure Shift + Arraste para mover a cena
- 🔄 **Reset**: Recarregue a página para voltar à posição inicial

## 🌟 Recursos do Modelo
- 🖼️ Texturas de alta resolução
- 💡 Iluminação realista
- 📱 Design responsivo (funciona em dispositivos móveis)
- ⚡ Performance otimizada

## 📦 Estrutura do Projeto

<div class="file-structure">
Dodge_Viper_3d/<br>
├── models/               # Arquivos do modelo 3D<br>
│   ├── viper.obj         # Modelo principal<br>
│   └── viper.mtl         # Materiais<br>
├── textures/             # Texturas do veículo<br>
├── js/                   # Scripts JavaScript<br>
│   └── main.js           # Configuração Three.js<br>
├── index.html            # Página principal<br>
├── LICENSE               # Licença MIT<br>
└── preview.jpg           # Imagem de preview
</div>

## 🚀 Como Executar Localmente

<div class="code-block">
1. Clone o repositório:<br>
<code>git clone https://github.com/ManoRicck/01-Dodge_Viper_3d.git</code>

2. Acesse a pasta do projeto:<br>
<code>cd 01-Dodge_Viper_3d</code>

3. Inicie um servidor local (recomendado):<br>
<code>npx serve</code>

4. Abra no navegador:<br>
<code>http://localhost:3000</code>
</div>

*Ou simplesmente abra o arquivo `index.html` diretamente no navegador*

## 🤝 Como Contribuir

1. Faça um fork do projeto
2. Crie sua branch de feature (`git checkout -b feature/incrivel`)
3. Commit suas mudanças (`git commit -m 'Adiciona feature incrível'`)
4. Push para a branch (`git push origin feature/incrivel`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

<div class="footer">
  <p>Feito com ❤️ por <a href="https://github.com/ManoRicck">ManoRicck</a></p>
  <img src="https://img.shields.io/badge/Powered%20by-Blender%20%26%20Three.js-ff7900?style=flat" alt="Powered by Blender and Three.js">
</div>

> ℹ️ Projeto criado para demonstração de modelos 3D interativos na web
