Eureka é uma solução de Service Discovery open source desenvolvida pela Netflix e é composta pelos módulos Eureka Server e Eureka Client.  

 

O Eureka Server consiste em uma aplicação que atua como Service Registry permitindo que outras aplicações registrem suas instâncias, com isso,  ele controla os endereços registrados mantendo-os atualizados e sinalizando quando um serviço não está disponível.
O Eureka Client é um componente Java que facilita a interação com Eureka Server.
 

Dentre as vantagens de se utilizar o Eureka estão:

 

É otimizado para trabalhar em AWS clouds com diferentes regiões;
O Eureka Client possui um serviço básico de load-balancing que utiliza a estratégia round-robin e pode ser utilizado quando não se deseja expor o serviço para o usuário final.
Clients não escritos em Java podem se comunicar com o Eureka Server através de uma API REST.
