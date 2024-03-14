# **Desafio**

## **Cenário:**

### **Objetivo:** Sua tarefa é criar os usuários de sistema para os funcionários da empresa **Smartspace** e os diretórios (pastas) para estes usuários ajustando as permissões para que apenas os usuários do grupo tenham acesso apenas aos arquivos de sua determinada área.


## **Grupos:**


### **Diretoria:**
|**Nome**|**Login**|
| - | - |
|Paulo Montenegro|paulo.montenegro|
|Daniel Melo|daniel.melo|



### **Gerência:**
|**Nome**|**Login**|
| - | - |
|Fernanda Alburquerque|fernanda.alburquerque|
|Eugênia Duarte|eugenia.duarte|



### **Logística:**
|**Nome**|**Login**|
| - | - |
|Marcelo Pereira|marcelo.pereira|
|Antônio da Costa|antonio.costa|




### **Departamento de TI:**
|**Nome**|**Login**|
| - | - |
|Ricardo Silva|ricardo.silva|
|andrio Campos|andrio.campos|
|Geraldo Cruz|geraldo.cruz|


## **Regras para criação e permissões das pastas:**

- Criar todos os usuários do organograma;
- Para facilitar defina a senha de todos os usuários como 123456;
- Criar os grupos diretoria, gerencia, logistica e ti;
- Inserir os usuários em seus respectivos grupos de acordo com o organograma;
- Criar as pastas diretoria, gerencia, logistica e ti em /mnt;
- O dono de todos os diretórios será o root e o grupo será o respectivo departamento;
- A diretoria pode acessar qualquer pasta (leitura e escrita);
- Os outros departamentos só podem acessar suas respectivas pastas;
- Deve existir um mecanismo para evitar que um usuário de um mesmo grupo remova arquivo que outro usuário criou;
- Os arquivos criados dentro destas pastas devem clonar dono e grupo da pasta para que os arquivos também sejam do grupo;
- O funcionário Ricardo Silva deverá ter seu login bloqueado por estar de ferias;
- O funcionário Marcelo Pereira está com sua conta bloqueada e deverá ser desbloqueada;
- A equipe de TI tem total acesso para virar root e não deve pedir senha ao executar o sudo;
- O diretores solicitaram a geração de uma senha segura com o comando dd para que ele memorizasse;
- Não esquecer de fazer um check-list para verificar se os usuários foram realmente criados, se as permissões e donos das pastas estão corretos.
