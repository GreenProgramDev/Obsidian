### #MVC
**O que é ->** é um padrão de arquitetura de software muito utilizado no desenvolvimento de aplicações web. O termo MVC é a abreviação de "Model-View-Controller" (Modelo-Visão-Controlador).

**Finalidade ->** É separar as preocupações das diferentes partes de uma aplicação, tornando-a mais organizada e de fácil manutenção.

#### Definição por Componente

**Model (modelo)**
	O Modelo representa a camada de dados e a lógica de negócios da aplicação. Ele é responsável por armazenar e manipular os dados, bem como implementar as regras de negócio do sistema.

**View (visão)** 
	A Visão é a camada de apresentação, responsável pela exibição dos dados para o usuário. Ela luida com a interface gráfica e a interação do usuário, como a exibição de páginas HTML, imagens, formulários etc.

**Controller (controlador)**
	O Controlador atua como um intermediário entre o Modelo e a Visão. Ele recebe as requisições do usuário da interface gráfica e manipula as ações apropriadas. Com base nessas ações, o Controller atualiza o Model e seleciona a View apropriada para apresentar os dados atualizados.

**Definição Geral**
	 A Separação dessas três camadas permite que as alteracões em uma parte do sistema não afetem necessariamente as outras. Por exemplo, se você precisar modificar a forma como os dados são apresentados ***View***, não será necessário alterar a lógica de negócio subjacente ***Model*** ou a forma como as ações são tratadas ***Controller***

**Utilizado em ->** Frameworks de desenvolvimento web, como ***Ruby on Rails***, ***Laravel PHP***, ***Django Python*** e ***ASP.NET C#***, entre outros. Ele oferece uma estutura organizada para o desenvolvimento de aplicações web, facilitando o trabalho em equipe e a manutenção a longo prazo do código.