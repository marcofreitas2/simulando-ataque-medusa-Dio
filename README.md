Nesta iniciativa, executei uma simulação de um ataque cibernético de quebra de senhas por força bruta (Brute Force) usando a ferramenta Medusa no sistema operacional Kali Linux. O objetivo foi testar a segurança em três protocolos de rede específicos: FTP (Protocolo de Transferência de Arquivos), HTTP (serviços web) e SMB (compartilhamento de recursos de rede).

O Que é um Ataque de Força Bruta
Um ataque de força bruta (Brute Force) é uma tática cibernética que se baseia em testes automatizados de tentativa e erro para desvendar credenciais de acesso (como nomes de usuário e senhas), chaves de criptografia ou URLs de páginas da web ocultas. O termo "força bruta" indica que a invasão utiliza programas de computador que testam exaustivamente e de forma metódica todas as combinações de caracteres possíveis até que a combinação correta seja descoberta. Essa metodologia de ataque é uma das mais antigas, mas continua sendo eficaz contra credenciais de login que são fracas.

Variações de Ataques de Quebra de Senha por Tentativa e Erro
Existem diversas modalidades de ataques de força bruta, cada uma com uma metodologia distinta:

Ataque Brute Force Simples: O cibercriminoso tenta adivinhar a senha manualmente, usando bom senso e lógica para testar combinações óbvias e previsíveis, como "123456", "password" ou datas de nascimento. Embora seja a abordagem menos sofisticada, ela ainda tem sucesso contra senhas que são extremamente vulneráveis.

Ataque de Dicionário: O agressor emprega listas predefinidas de palavras (conhecidas como dicionários) para testar como possíveis senhas. Essas listas abrangem vocabulário comum em diferentes línguas, nomes, terminologias técnicas e outros dados que as pessoas frequentemente escolhem para suas senhas.

Ataque Híbrido: Esta técnica é um amálgama do ataque de dicionário com a força bruta simples. O software do invasor usa uma lista de palavras-base e, em seguida, gera variações a partir delas, como incluir dígitos no final ("senha123"), letras maiúsculas no início ("Password123") ou substituir caracteres por símbolos semelhantes ("p4ssw0rd").

Ataque de Pulverização de Senhas (Password Spraying): Em vez de testar inúmeras senhas em uma única conta (o que geralmente leva ao bloqueio da conta), o invasor tenta uma ou poucas senhas comuns (exemplo: "password123") em muitas contas diferentes. Este método tem como objetivo contornar os mecanismos de defesa que bloqueiam contas após um alto número de tentativas falhas consecutivas, característicos dos ataques de força bruta tradicionais.

Ataque de Força Bruta Reversa: O processo é invertido: o invasor começa com uma senha que já é conhecida (muitas vezes obtida a partir de vazamentos de dados) e a testa em milhões de nomes de usuário até identificar o par de credenciais válido.
