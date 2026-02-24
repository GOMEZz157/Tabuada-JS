# 📘 Tabuada JS

Gerador de tabuada desenvolvido com **HTML, CSS e JavaScript (Vanilla JS)**.  
O usuário informa o número base da tabuada e até qual número deseja multiplicar.  
O resultado é exibido dinamicamente na página utilizando **manipulação do DOM** e **template strings**.

🔗 **Repositório:**  
https://github.com/GOMEZz157/Tabuada-JS  

🔗 **Deploy:**  
https://tabuada-js-six.vercel.app  

---

## 🚀 Funcionalidades

- Gerar tabuada de qualquer número
- Definir o limite de multiplicação
- Renderização dinâmica no HTML
- Uso de template strings para montar cada linha da tabuada
- Validação de entrada com `isNaN()`
- Permite o número `0` como valor válido
- Mensagens de erro para entradas inválidas

---

## 🧠 Conceitos Aplicados

- Manipulação do DOM (`querySelector`, `appendChild`, `innerHTML`)
- Eventos (`submit` e `preventDefault`)
- Estrutura de repetição (`for`)
- Template strings (`` `${n} x ${i} = ${n * i}` ``)
- Conversão de tipos com `Number()`
- Validação de dados com `isNaN()`
- Organização de projeto separando HTML, CSS e JS

---

## 📂 Estrutura do Projeto

```
.
├── index.html
├── css/
│   └── style.css
└── js/
    └── scripts.js
```

---

## 🔎 Validação Implementada

Para evitar falhas com valores inválidos e permitir o uso do número `0`, foi aplicada a seguinte validação:

```javascript
if (isNaN(multiplicationNumber) || isNaN(multiplicatorNumber)) {
  alert("Por favor, insira números válidos.");
  return;
}

if (multiplicatorNumber <= 0) {
  alert("O valor 'Multiplicar até' deve ser maior que 0.");
  return;
}
```

Essa abordagem impede entradas inválidas e melhora a experiência do usuário.

---

## ▶️ Como Executar

1. Clone o repositório:

```
git clone https://github.com/GOMEZz157/Tabuada-JS.git
```

2. Entre na pasta:

```
cd Tabuada-JS
```

3. Abra o arquivo `index.html` no navegador  
ou utilize a extensão **Live Server** no VS Code.

---

## 💡 Melhorias Futuras

- Adicionar botão para limpar resultados
- Melhorar responsividade
- Adicionar animação na geração da tabuada
- Permitir gerar múltiplas tabuadas simultaneamente

---

## 📄 Licença

Projeto desenvolvido para fins de estudo e prática em JavaScript.
