#### Politicas da Função Lambda:

- Na pagina da função, clique em Configurações > Permissões;

- Clique na Role e uma nova aba será aberta;

- Clique em *Adicionar permissões* e em *Criar política em linha*;

- Clique em JSON e cole o seguinte código:

  - {
        "Version": "2012-10-17",
        "Statement": [
            {
                "Sid": "VisualEditor0",
                "Effect": "Allow",
                "Action": [
                    "ec2:Start\*",
                    "ec2:Stop\*",
                ],
                "Resource": "*"
            }
        ]

  
  
  
  
  