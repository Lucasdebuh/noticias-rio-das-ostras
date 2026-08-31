# 🌊 Notícias Rio das Ostras

Portal moderno de notícias dedicado a trazer as principais informações sobre Rio das Ostras e região.

## 📋 Características

- ✨ **Interface Responsiva** - Otimizado para desktop, tablet e mobile
- 🔍 **Busca em Tempo Real** - Filtre notícias instantaneamente
- 🏷️ **Categorias** - Política, Cultura, Turismo, Esportes
- 📱 **Feed Dinâmico** - Carrega notícias do arquivo `feed-data.json`
- 🌙 **Modo Escuro** - Suporte completo a temas claro e escuro
- ⚡ **Performance** - Página leve e rápida

## 📁 Estrutura do Projeto

```
noticias-rio-das-ostras/
├── index.html          # Página principal
├── feed-data.json      # Dados das notícias
└── README.md          # Este arquivo
```

## 🚀 Como Usar

### Visualizar Online
1. Abra `index.html` em um navegador web
2. O site carregará automaticamente as notícias de `feed-data.json`

### Estrutura do Feed Data

O arquivo `feed-data.json` contém:

```json
{
  "metadata": {
    "version": "1.0",
    "lastUpdated": "ISO-8601 timestamp",
    "sources": [
      {
        "name": "Nome da Fonte",
        "url": "https://instagram.com/...",
        "postsCollected": 5
      }
    ]
  },
  "feed": [
    {
      "id": "id_unico",
      "source": "Rio das Ostras 24H",
      "source_url": "https://www.instagram.com/riodasostras24h/",
      "title": "Título da Notícia",
      "description": "Descrição breve",
      "date": "ISO-8601 timestamp",
      "category": "politica|cultura|turismo|esportes",
      "original_post": "https://instagram.com/p/..."
    }
  ],
  "statistics": {
    "totalPosts": 12,
    "byCategory": {...},
    "bySource": {...}
  }
}
```

## 📚 Fontes de Notícias

As notícias são coletadas de:
- [Rio das Ostras 24H](https://www.instagram.com/riodasostras24h/)
- [Germano Junior](https://www.instagram.com/germanojunior343/)
- [LP News Portal Oficial](https://www.instagram.com/lpnewsportaloficial/)

Todos os créditos e links originais são preservados em cada notícia.

## 🎨 Design

- **Paleta de Cores**: Inspirada na identidade costeira de Rio das Ostras
  - Azul Oceano: `#0F4C75`
  - Laranja Coral: `#E67E22`
  - Neutro Claro: `#F5F1E8`

- **Tipografia**:
  - Display: Playfair Display (títulos)
  - Body: Inter (conteúdo)
  - Mono: Roboto Mono (datas e dados)

## 🔧 Desenvolvimento

### Adicionar Novas Notícias

1. Edite `feed-data.json`
2. Adicione um novo objeto na array `feed`
3. Mantenha o mesmo formato e estrutura
4. As notícias são ordenadas automaticamente por data (mais recentes primeiro)

### Filtros Disponíveis

- **Todas** - Mostra todas as notícias
- **Política** - Notícias sobre política e governo
- **Cultura** - Eventos culturais e artísticos
- **Turismo** - Informações turísticas
- **Esportes** - Eventos esportivos

## 📝 Atualização do Feed

Para atualizar o feed com novas notícias:

1. Acesse as fontes do Instagram
2. Colete os posts públicos mais recentes
3. Estruture os dados conforme `feed-data.json`
4. Preserve os créditos e links originais
5. Ordene do mais recente para o mais antigo

## 🌐 Compatibilidade

- ✅ Chrome/Edge (última versão)
- ✅ Firefox (última versão)
- ✅ Safari (última versão)
- ✅ Mobile browsers (iOS/Android)

## 📄 Licença

Este projeto é de código aberto. Créditos às fontes originais são preservados em cada notícia.

## 👤 Autor

Lucas Moreira Marini - [GitHub](https://github.com/Lucasdebuh)

---

**Última atualização**: 31 de agosto de 2026
**Notícias no feed**: 12
**Fontes ativas**: 3