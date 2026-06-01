# Política de Privacidade

**Aplicação Móvel:** UAS BVCE - Pre-flight Checklist  
**Entidade Responsável:** Bombeiros Voluntários do Concelho de Espinho (BVCE)  
**Última Atualização:** Junho de 2026  

Os **Bombeiros Voluntários do Concelho de Espinho (BVCE)** valorizam a privacidade e a segurança dos dados dos seus operadores de sistemas de aeronaves não tripuladas (UAS). Esta Política de Privacidade explica de que forma a aplicação móvel **UAS BVCE** trata as informações no âmbito das operações de pré-voo.

> [!NOTE]
> **Resumo Operacional:**  
> A aplicação foi desenhada para priorizar a soberania e a segurança dos dados operacionais. A recolha de dados é efetuada estritamente para cumprir exigências operacionais e legais de segurança aérea (ANAC / EASA), sendo os dados armazenados exclusivamente no dispositivo.

---

## 1. Informações Recolhidas e Finalidades

* **Localização do Dispositivo:** A aplicação solicita acesso à localização GPS (coarse e fine location) do dispositivo móvel. Este acesso serve unicamente para ler as coordenadas geográficas do local da operação de voo e preencher automaticamente a checklist regulamentar de pré-voo. A localização é processada e gravada apenas no próprio dispositivo.
* **Dados de Telemetria e Baterias (DJI SDK):** Para efetuar a monitorização em tempo real e sincronizar dados de saúde das baterias DJI TB30, a aplicação utiliza a biblioteca nativa da DJI. Os dados de telemetria da aeronave e das baterias ligadas ao comando (RC) são lidos localmente. O processo de autenticação e validação de licenças do SDK liga-se diretamente aos servidores da DJI (DJI Cloud API), de acordo com os termos de privacidade da própria DJI.
* **Relatórios e Checklists de Voo:** Todas as checklists de pré-voo concluídas são guardadas exclusivamente na memória local do dispositivo (armazenamento persistente local via `AsyncStorage`).

---

## 2. Partilha de Dados

A aplicação não transmite as checklists concluídas ou os dados de localização para quaisquer servidores de terceiros ou base de dados externa dos BVCE. A partilha de relatórios de voo (como ficheiros PDF gerados pela app) é efetuada **manualmente e sob total controlo do utilizador**, através das opções nativas do sistema operativo (email, aplicações de mensagens, etc.).

---

## 3. Armazenamento e Segurança dos Dados

Como os dados persistidos pela aplicação são guardados apenas no armazenamento seguro local do dispositivo do utilizador, a segurança física e digital das checklists guardadas depende da segurança do próprio dispositivo móvel.

---

## 4. Direitos dos Utilizadores

O utilizador tem controlo total sobre os seus dados operacionais na aplicação. A qualquer momento poderá:
* Consultar ou eliminar registos individuais ou a totalidade do histórico de checklists no ecrã de histórico da aplicação.
* Revogar a autorização de acesso à localização GPS nas definições de permissões do sistema operativo Android.
* Apagar definitivamente todos os dados locais desinstalando a aplicação ou limpando o armazenamento de dados da app nas definições do sistema.

---

## 5. Alterações a esta Política

Esta Política de Privacidade pode ser atualizada ocasionalmente para refletir alterações operacionais ou regulamentares. Recomendamos a consulta periódica desta página para se manter informado sobre como protegemos as suas informações.

---

## 6. Contacto

Para qualquer esclarecimento adicional sobre esta política ou sobre o funcionamento da aplicação, por favor contacte a equipa de comando dos Bombeiros Voluntários do Concelho de Espinho ou o programador responsável.

---
*Desenvolvido para suporte a missões de emergência e proteção civil.*
