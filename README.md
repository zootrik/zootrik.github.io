<div align="center">

# ZOOTRIK

### `Gratuito` · `Offline-first` · `Cuidados com pets`

[![App](https://img.shields.io/badge/app-abrir_painel-0F766E?style=for-the-badge)](https://zootrik.github.io/)
[![Site](https://img.shields.io/badge/site-oficial-134E4A?style=for-the-badge)](https://zootrik.github.io/)
[![Repositório](https://img.shields.io/badge/c%C3%B3digo-fonte-181717?style=for-the-badge&logo=github)](https://github.com/zootrik/zootrik.github.io)
[![Apoie](https://img.shields.io/badge/apoie-o_projeto-009EE3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://link.mercadopago.com.br/saulomgg)

</div>

---

## `> whoami`

```bash
$ cat /dev/zootrik
Nome:   Zootrik · rotina e cuidados com pets
Foco:   tarefas · saúde · vacinas · peso · despesas
Modo:   PWA instalável · offline-first · dados locais
Nuvem:  opcional · Google Sheets e Google Calendar
Idiomas: Português · English · Español
```

O **Zootrik** ajuda a organizar os cuidados do dia a dia dos seus animais. Reúna rotinas, vacinas, registros de saúde, peso e despesas em um só painel, com privacidade local por padrão.

O app pode ser instalado no celular ou computador e usado offline. Você pode começar sem perfil. Se quiser sincronizar entre dispositivos, há uma opção de conexão com seus próprios serviços Google.

---

## `> ls ./recursos`

| Recurso | O que você encontra |
| --- | --- |
| 🐾 **Pets** | Cadastro de cães, gatos, pássaros, coelhos, hamsters, tartarugas, peixes e outros animais, com informações de idade, raça, peso, alimentação, veterinário e observações de saúde |
| ✅ **Painel e tarefas** | Progresso diário, tarefas, alertas de saúde e visão geral das rotinas dos pets |
| 💉 **Saúde e vacinas** | Registros de vacinas, vermífugos, prevenção contra pulgas e carrapatos e visitas ao veterinário, com alertas de próximas datas |
| ⚖️ **Peso** | Histórico e acompanhamento da evolução do peso dos animais |
| 💰 **Despesas** | Registro de gastos mensais relacionados aos pets |
| 📅 **Calendário** | Lembretes e eventos para rotinas e datas de saúde, com integração opcional ao Google Calendar e exportação de arquivo `.ics` |
| ☁️ **Sincronização** | Integração opcional entre dispositivos usando Google Apps Script e uma planilha Google da sua conta |
| 💾 **Backup** | Cópia local em JSON e exportação de dados em CSV |
| 🌐 **Idiomas e aparência** | Interface em português, inglês e espanhol, com tema claro ou escuro e opções de cor |

---

## `> cat ./privacidade`

```json
{
  "perfil": "opcional",
  "armazenamento": "no dispositivo por padrão",
  "rastreamento": false,
  "modo_offline": true,
  "sincronizacao_google": "opcional, configurada pelo usuário",
  "backup": ["JSON", "CSV"]
}
```

- **Dados locais por padrão:** o Zootrik informa que os dados ficam no dispositivo. O uso principal não exige envio dos registros dos pets a um servidor do projeto.

- **Sem perfil obrigatório:** você pode continuar sem criar um perfil. O formulário permite preencher dados do responsável, com e-mail e telefone opcionais.

- **Nuvem opcional:** para transferir dados entre dispositivos, conecte o app a uma planilha Google sua por meio de Google Apps Script. A configuração e a sincronização exigem internet e autorização da sua conta Google.

- **Calendário opcional:** você pode gerar lembretes no Google Calendar ou usar notificações locais e arquivos `.ics`, conforme a opção escolhida.

- **Backup:** use o backup JSON para guardar e restaurar seus dados. A exportação CSV permite manter uma cópia tabular.

> [!NOTE]
A sincronização com Google Sheets e Google Calendar envolve os serviços e as permissões da sua própria conta Google. Faça backups regulares e guarde os arquivos em local seguro.

---

## `> ./iniciar`

```bash
1. Acesse   zootrik.github.io
2. Comece   continue sem perfil ou preencha os dados opcionais do responsável
3. Cadastre adicione seu primeiro pet
4. Organize registre tarefas, cuidados de saúde, peso e despesas
5. Instale  use "Install App" para adicionar o PWA à tela inicial
6. Proteja  exporte um backup JSON ou configure a sincronização opcional
```

[▶ **Abrir o Zootrik**](https://zootrik.github.io/)

---

## `> ping apoio`

O Zootrik é um projeto gratuito e independente. Contribuições voluntárias ajudam a manter as melhorias e o desenvolvimento de novas ferramentas.

[![Apoie pelo Mercado Pago](https://img.shields.io/badge/%F0%9F%92%9B_Apoie_pelo_Mercado_Pago-009EE3?style=for-the-badge&logo=mercadopago&logoColor=white)](https://link.mercadopago.com.br/saulomgg)

[Roadmap e apoio](https://zootrik.github.io/#support)

---

## `> ping links`

| Canal | Link |
| --- | --- |
| Zootrik · App | [zootrik.github.io](https://zootrik.github.io/) |
| Repositório | [github.com/zootrik/zootrik.github.io](https://github.com/zootrik/zootrik.github.io) |
| Roadmap e apoio | [zootrik.github.io/#support](https://zootrik.github.io/#support) |
| Hub de apps | [saulomgg.github.io](https://saulomgg.github.io/) |
| Feedback | [Enviar sugestão](mailto:saulomg2@hotmail.com?subject=%5BZootrik%20Feedback%5D%20Sugest%C3%A3o%20%2F%20Melhoria) |
| Instagram | [@saulo_mgg](https://instagram.com/saulo_mgg) |
| YouTube | [@saulomgg](https://youtube.com/@saulomgg) |
| Telegram | [S0M9Net](https://t.me/S0M9Net) |
| LinkedIn | [saulomgg](https://linkedin.com/in/saulomgg) |
| Apoio · Mercado Pago | [link.mercadopago.com.br/saulomgg](https://link.mercadopago.com.br/saulomgg) |

---

## `> cat ./LICENSE`

Consulte o arquivo [`LICENSE`](./LICENSE) para os termos de uso e direitos autorais. A licença deste pacote é proprietária e **não** é uma licença open-source permissiva. O site do Zootrik o descreve como “open-source”; essa descrição precisa ser alinhada à licença antes da publicação.

---

<div align="center">

Desenvolvido por [**Saulo (saulomgg)**](https://saulomgg.github.io/) · cuidado e rotina dos seus pets

```
┌─────────────────────────────────────────────┐
│  [ SYSTEM ]  Zootrik · pet care             │
│  [ STATUS ]  Offline-first · privado        │
│  [ DATA   ]  Local · sincronização opcional │
│  [ BACKUP ]  JSON · CSV · Google*           │
│  [ * ]       Conectado na sua conta Google  │
└─────────────────────────────────────────────┘
```

</div>
