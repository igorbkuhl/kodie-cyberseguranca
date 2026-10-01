Nome: Igor Borges Kühl
Data: 28/08/2026

Incidente: Leaker Midnight Eclipse – Blog Barracuda, 19/05/2026
https://blog.barracuda.com/2026/05/19/nightmare-eclipse-zero-days-grudge

* Modelo CIA
Confidencialidade - Os programas maliciosos fornecidos ultrapassam as barreiras de segurança do sistema.
Integridade - Alguns dos programas alteram nível de acesso do usuário para SYSTEM (BlueHammer, RedSun, MiniPlasma).
Disponibilidade - Os ataques não buscam derrubar nenhum serviço.

* Cadeia de Ataque
1. Reconhecimento - Medidas de garantir que apenas funcionários atuais terão acesso interno aos serviços.
2. Entrega - Escaneamento de código nocivo no GitHub.
3. Exploração - Mais padrões de detecção nos antivirus.
4. Persistência - Reconhecimento do Windows em quais métodos um usuário usou para alcançar permissões nível SYSTEM.
5. Exfiltração - Proteção mais robusta do BitLocker contra dispositivos físicos.

* Mitre Att&ck
T1200 - Hardware Additions - M1034 (Limit Hardware Installation)
T1195 - Supply Chain Compromise - M1046 (Boot Integrity)

* Conclusão
O ransomware foi executado através de exploração de hardware (T1200) e comprometimento do sistema de segurança do Windows (T1195). A pessoa por trás dos vazamentos não teria motivação caso a Microsoft valorizasse mais seu setor de tecnologia.
