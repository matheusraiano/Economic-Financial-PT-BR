# Guia de Instalação - Economic & Financial PT-BR

Este guia fornece instruções detalhadas para instalar a tradução PT-BR do Economic & Financial Mod.

## 📋 Requisitos

- ✅ Victoria 3 instalado e atualizado
- ✅ Mod original [Economic & Financial](https://steamcommunity.com/sharedfiles/filedetails/?id=3143591632) instalado
- ✅ Espaço em disco: ~3 MB

## 🚀 Método 1: Steam Workshop (Recomendado)

### Passo 1: Instalar o Mod Original
1. Acesse a página do [Economic & Financial Mod](https://steamcommunity.com/sharedfiles/filedetails/?id=3143591632)
2. Clique em **"Inscrever-se"** (Subscribe)
3. Aguarde o download automático

### Passo 2: Instalar a Tradução PT-BR
1. Acesse a página da tradução PT-BR na Steam Workshop
2. Clique em **"Inscrever-se"** (Subscribe)
3. Aguarde o download automático

### Passo 3: Ativar os Mods
1. Abra o **Launcher do Victoria 3**
2. Vá para a aba **"Mods de Jogo"**
3. Ative ambos os mods na seguinte ordem:
   ```
   ☑ Economic & Financial Mod
   ☑ Economic & Financial PT-BR
   ```
4. Clique em **"Jogar"**

## 💾 Método 2: Instalação Manual

### Passo 1: Download
1. Vá para a página de [Releases](../../releases)
2. Baixe a última versão: `Economic-Financial-PT-BR-v1.0.zip`
3. Extraia o arquivo ZIP

### Passo 2: Localizar a Pasta de Mods
Encontre a pasta de mods do Victoria 3 no seu sistema:

**Windows:**
```
C:\Users\[SeuUsuario]\Documents\Paradox Interactive\Victoria 3\mod\
```

**Linux:**
```
~/.local/share/Paradox Interactive/Victoria 3/mod/
```

**Mac:**
```
~/Documents/Paradox Interactive/Victoria 3/mod/
```

### Passo 3: Copiar os Arquivos
1. Copie a pasta `Economic&Financial PT-BR` para a pasta `mod\`
2. A estrutura deve ficar assim:
   ```
   mod\
   └── Economic&Financial PT-BR\
       ├── .metadata\
       │   └── metadata.json
       └── localization\
           └── braz_por\
               ├── 00_ef_amandement_localization_l_braz_por.yml
               ├── 00_ef_gui_localization_l_braz_por.yml
               └── ... (mais 16 arquivos)
   ```

### Passo 4: Ativar no Launcher
1. Abra o **Launcher do Victoria 3**
2. Vá para a aba **"Mods de Jogo"**
3. Ative os mods:
   ```
   ☑ Economic & Financial Mod
   ☑ Economic & Financial PT-BR
   ```
4. Clique em **"Jogar"**

## ⚠️ Solução de Problemas

### O mod não aparece no launcher
**Solução:**
1. Verifique se a pasta está no local correto
2. Certifique-se de que o arquivo `metadata.json` existe
3. Reinicie o launcher do Victoria 3

### Textos ainda aparecem em inglês
**Problema:** O mod original está carregando depois da tradução

**Solução:**
1. No launcher, arraste os mods para reordenar:
   - Economic & Financial Mod (primeiro)
   - Economic & Financial PT-BR (segundo)
2. Ou edite manualmente o arquivo `dlc_load.json`

### Caracteres estranhos (�, □, etc.)
**Problema:** Codificação incorreta

**Solução:**
1. Baixe novamente a versão mais recente
2. Todos os arquivos devem ter codificação UTF-8 com BOM
3. Se o problema persistir, reporte no [GitHub Issues](../../issues)

### Ícones de moedas não aparecem
**Problema:** Arquivo de currency_name está faltando ou corrompido

**Solução:**
1. Verifique se o arquivo `01_ef_currency_name_localization_l_braz_por.yml` existe
2. Reinstale o mod
3. Certifique-se de que o mod original está ativo

## ✅ Verificação da Instalação

Para verificar se a instalação foi bem-sucedida:

1. Inicie um novo jogo ou carregue um save
2. Abra o menu **"Economia"** (deve estar em português)
3. Verifique os tooltips ao passar o mouse sobre os ícones
4. Se tudo estiver em português, a instalação foi bem-sucedida! 🎉

## 🔄 Atualização

### Steam Workshop
A atualização é automática. Basta garantir que o mod está inscrito.

### Instalação Manual
1. Baixe a nova versão
2. Delete a pasta antiga `Economic&Financial PT-BR`
3. Copie a nova versão para a pasta `mod\`
4. Reinicie o launcher

## 🆘 Precisa de Ajuda?

- 📖 Leia o [README.md](README.md)
- 🐛 Reporte bugs no [GitHub Issues](../../issues)
- 💬 Discussões no [GitHub Discussions](../../discussions)

---

**Bom jogo! 🎮**
