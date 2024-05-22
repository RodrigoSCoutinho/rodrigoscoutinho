<h2 align="center" style="font-family: Consolas, monospace;">
    [~] $ whoami
</h2>

## What's up, I'm Rodrigo.
<h5>Software Enginner from Brazil, I turn lines of code into experiences that shape the future.</h5>

- 🔭 I currently work with microservices in Java.
- 💬 Ask me about Computer Architecture.
- 💻 Information Systems at [IFRN](https://portal.ifrn.edu.br/)

```bash
#!/bin/bash

echo "Conectando à Cafeteria..."
echo "Bem-vindo, $USER!"

while true; do
  echo -e "\nMenu:\n1. Espresso\n2. Latte\n3. Cappuccino\n4. Mocha\n5. Macchiato\n6. Sair"
  read -p "Escolha seu café: " choice
  case $choice in
    1) echo "Espresso a caminho..." ;;
    2) echo "Latte a caminho..." ;;
    3) echo "Cappuccino a caminho..." ;;
    4) echo "Mocha a caminho..." ;;
    5) echo "Macchiato a caminho..." ;;
    6) echo "Saindo..." && exit 0 ;;
    *) echo "Opção inválida" ;;
  esac
  echo "Seu café está pronto! ☕"
done
