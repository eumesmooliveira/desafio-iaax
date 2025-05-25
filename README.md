# 🚀 Solução do Desafio AIAX

<div align="center">
  <img src="https://img.icons8.com/color/96/000000/python.png" alt="Python logo"/>
</div>

## 📋 Descrição
Script Python que:
1. Baixa uma imagem específica via scraping
2. Processa com a API Microsoft Florence-2
3. Submete a análise automática

## 🛠️ Tecnologias
| Biblioteca | Função |
|------------|--------|
| `requests` | Chamadas à API |
| `Pillow`   | Redimensionamento de imagem |
| `BeautifulSoup` | Extração da URL da imagem |

## 🖥️ Como Executar
```bash
# 1. Instale as dependências
pip install requests Pillow beautifulsoup4

# 2. Configure o token (Linux/Mac)
export API_TOKEN="seu_token"

# 3. Execute
python desafioIA.py
```

## 🌟 Destaques
- Tratamento de 5 tipos de erros HTTP
- Redimensionamento automático de imagens
- Sistema de fallback para múltiplos formatos de payload

*Desenvolvido com 💙 por Felipe de Oliveira*
