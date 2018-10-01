## Experiências/Dicas/Sugestões

- Alguns gráficos foram plotados diretamente no documento principal, o que o polui desnecessariamente, outros plotados no matlab e depois exportados, o que torna difícil manter um padrão.

**Sugestão:** Plotar cada gráfico em um arquivo `.tex` separado, usando a classe `standalone`, e incluir o pdf gerado no documento principal.

---

- A classe `ufsc-thesis` não foi instalada/configurada/não funcionou direito.

**Sugestão:** Ou usar a classe completamente, da forma correta, ou não usar e configurar o documento manualmente. Usando parcialmente fica uma bagunça.

---

- Os comentários, nomes dos arquivos, mensagens dos commits, etc. estão em inglês e o texto em português.

**Sugestão:** Fazer tudo em uma única língua, salvo quando for atrapalhar o desenvolvimento, por exemplo, quando o texto for em português e os comandos do Latex em inglês.
