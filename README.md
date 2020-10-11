# Interface

### Objetivo
Exercício prático de POO para desenvolver os conceitos do uso de interface, estabelecendo um contrato para a clase ```BrazilTaxservice``` implentar o método ```tax``` da interface ```TaxService```

### Exercício proposto
Uma locadora brasileira de carros cobra um valor por hora para locações de até 12 horas. Porém, se a duração da locação ultrapassar 12 horas, a locação será cobrada com base em um valor diário. Além do valor da locação, é acrescido no preço o valor do imposto conforme regras do país que, no caso do Brasil, é 20% para valores até 100.00, ou 15% para valores acima de 100.00. 
Fazer um programa que lê os dados da locação (modelo do carro, instante inicial e final da locação), bem como o valor por hora e o valor diário de locação. O programa deve então gerar a nota de pagamento (contendo valor da locação, valor do imposto e valor total do pagamento) e informar os dados na tela. Veja os 
exemplos. Implementar o exercício conforme o diagrama de classe:

### Diagrama de classes
<p align="center">
  <img src="https://raw.githubusercontent.com/cernandes/interface-java/master/assets/img/diagram-class-domain-layer.jpg" width="350" title="hover text" alt="class diagram">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/cernandes/interface-java/master/assets/img/diagram-class-service-layer.JPG" width="350" title="hover text" alt="class diagram">
</p>

#### cas #1
<p>Primeiro caso com datas de retirada e entrega no mesmo dia</p>

<p>Enter rental data</p>
Car model: <span style="color: red">Civic</span><br>
Pickup (dd/MM/yyyy HH:mm): <span style="color: red">25/06/2020 10:30</span><br>
Retun (dd/MM/yyyy HH:mm): <span style="color: red">25/06/2020 14:30</span><br>
Enter price per hour: <span style="color: red">10.00</span><br>
Enter price per day: <span style="color: red">130.00</span><br>

```
Invoice:
Basic payment: 50.00
Tax: 10.00
Total payment: 60.00
```
#### caso #2
<p>Segundo caso com entrega dois dias após a retirada</p>

<p>Enter rental data</p>
Car model: <span style="color: red">Civic</span><br>
Pickup (dd/MM/yyyy HH:mm): <span style="color: red">25/06/2020 10:30</span><br>
Retun (dd/MM/yyyy HH:mm): <span style="color: red">27/06/2020 11:30</span><br>
Enter price per hour: <span style="color: red">10.00</span><br>
Enter price per day: <span style="color: red">130.00</span><br>

```
Invoice:
Basic payment: 390.00
Tax: 58.50
Total payment: 448.50
```
### Referência
Projeto inspirado em aulas do curso de POO com java da [Udemy](https://www.udemy.com/course/java-curso-completo) 

### Autor 
@[Claudio Ernandes](https://github.com/cernandes)
