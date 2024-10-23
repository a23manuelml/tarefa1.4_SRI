## Tarefa 1.4 Instalación de zonas secundarias con Windows Server.

1. Tomaremos a máquina benskywalker, e configuraremola para ser servidor secundario, tanto da zona primaria academia.jedi de resolución directa como de resolución inversa. Captura a configuración en ambalas dúas máquinas.

    - Configuración TCP/IP do servidor benskywalker

        ![imaxe1](imaxes/solapt1.1.png)

    - Indicamos, no equipo lukeskywalker, nas zonas, que se van a poder transferir ó outro servidor (benskywalker)

        ![imaxe2](imaxes/solapt1.2.png)

    - Comprobamos a transferencia das zonas no servidor benskywalker

        ![imaxe3](imaxes/solapt1.3.png)
    
2. Engade un rexistro tipo A (yaddle 192.168.20.107) na zona de resolución directa e tamén na de resolución inversa. Adxunta captura dos rexistros da zona unha vez feita a transferencia.

    - Engadimos rexistor tipo A yaddle na zona directa:

        - Lukeskywalker:

            ![imaxe4](imaxes/solapt2.1.png)
        
        - Benskywalker:

            ![imaxe5](imaxes/solapt2.2.png)
    
    - Engadimos rexistro PTR yaddle na zona inversa:

        - Lukeskywalker:

            ![imaxe6](imaxes/solapt2.3.png)

        - Benskywalker.

            ![imaxe7](imaxes/solapt2.4.png)
    