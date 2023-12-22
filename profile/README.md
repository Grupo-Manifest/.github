## Manifest: Kowalski

Projeto desenvolvido durante a graduação para uma empresa parceira. <br>
Consiste em mimetizar a aparência do aplicativo da empresa, adicionando novas funcionalidades que melhorem a experiência do usuário. <br>

As novas features são:  <br>

1) Sistema de avaliações: <br>
  - O aplicativo original contém um mapa com a posição de seus estabelecimentos e algumas informações. <br>
  - Nós adicionamos a opção de avaliar os serviços prestados e uma lista, onde o usuário pode ver os estabelecimentos ordenados pela nota. <br>

2) Pagamento simplificado: <br>
  - Alguns dos estabelecimentos possuem um código numérico, possibilitando o pagamento via aplicativo. <br>
  - Adicionamos um leitor de caracteres, para que o usuário não precise inserir o código manualmente, e um leitor de códigos QR, dando margem para uma atualização de tecnologias. <br>

3) Leitor de sensor OBD*: <br>
  - Para promover o uso do aplicativo, desenvolvemos um sistema que leria dados de um sensor compatível com o protocolo OBD via Bluetooth ou Web Sockets. <br>
  - Este protocolo permite a leitura dos dados de sensores de um veículo. <br>
  - Este módulo do projeto permite que o usuário tenha um controle maior sobre seu veículo, ajudando-o a tomar decisões relativas à manutenção. <br>
  - O sistema ainda mandaria notificações em casos que podem se tornar críticos, auxiliando a manter a saúde veicular. <br>

  > *Nota: o protocolo OBD é proprietário e, por isso, não é possível implementá-lo completamente.  <br>
  > A aplicação ilustra seu funcionamento, sendo responsabilidade da empresa cliente a negociação da licença para se utilizar o protocolo.  <br>

O aplicativo foi desenvolvido nativamente para Android, utilizando a linguagem Kotlin, organizado seguindo o modelo de arquiterura MVVM.
