# info5100-assignment-5-solved
**TO GET THIS SOLUTION VISIT:** [INFO5100 Assignment 5 Solved](https://www.ankitcodinghub.com/product/info5100-assignment-5-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94986&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;INFO5100 Assignment 5 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1) Implement the below Diagram for decorator pattern. Test using code given below.

</div>
</div>
<div class="layoutArea">
<div class="column">
Interface

ICar

assemble() : void

</div>
</div>
<div class="layoutArea">
<div class="column">
Class

BasicCar

BasicCar() assemble() : void

</div>
</div>
<div class="layoutArea">
<div class="column">
Class

CarDecorator

CarDecorator(Car) assemble() : void

</div>
</div>
<div class="layoutArea">
<div class="column">
Class

LuxuryCar

LuxuryCar(Car) assemble() : void

</div>
</div>
<div class="layoutArea">
<div class="column">
Class

SportsCar

SportsCar(Car) assemble() : void

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
public class DecoratorPatternTest {

public static void main(String[] args) {

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Car sportsCar = new SportsCar(new BasicCar()); sportsCar.assemble();

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
System.out.println();

Car sportsLuxuryCar = new SportsCar(new LuxuryCar(new BasicCar()));

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
sportsLuxuryCar.assemble(); }

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
}

o/p:

Basic Car. Adding features of Sports Car.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Basic Car. Adding features of Luxury Car. Adding features of Sports Car.

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2) Implement the below Diagram for Façade design pattern. Test using code given below.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Interface

Shape

draw() : void

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Class

ShapeMaker

circle : Shape rectangle: Shape square : Shape

ShapeMaker() drawCircle() : void drawRectangle() : void drawSquare() : void

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Class

Circle

draw() : void

</div>
</div>
<div class="layoutArea">
<div class="column">
Class

Rectangle

draw() : void

</div>
</div>
<div class="layoutArea">
<div class="column">
Class

Square

draw() : void

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
public class FacadePatternDemo {

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
public static void main(String[] args) { ShapeMaker shapeMaker = new ShapeMaker();

shapeMaker.drawCircle(); shapeMaker.drawRectangle();

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
shapeMaker.drawSquare(); }

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
} O/P:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Drawing a Circle

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Drawing a Rectangle Drawing a Square

</div>
</div>
</td>
</tr>
<tr>
<td></td>
</tr>
<tr>
<td></td>
</tr>
<tr>
<td></td>
</tr>
<tr>
<td></td>
</tr>
<tr>
<td></td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
3) Implement the below Diagram for Strategy pattern. Test using code given below.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Class

ShoppingCart

ShoppingCart() addItem(Item) : void removeItem(Item) : void

calculateTotal() : int pay(PaymentStrategy) : void

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Interface

PaymentStrategy

pay(int) : void

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Class

CreditCard

cardNumber : String

CreditCard(String) pay(int) : void

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Class

PayPal

email : String

PayPal(String) pay(int) : void

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Class

Item

Id : String price : int

Item(String, int) getId() : String getPrice() : int

</div>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
public class StrategyPatternDemo {

public static void main(String[] args) {

ShoppingCart cart = new ShoppingCart();

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Item item1 = new Item(“1234”,10); Item item2 = new Item(“5678”,40);

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
cart.addItem(item1); cart.addItem(item2);

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
cart.pay(new PaypalStrategy(“myemail@example.com”)); cart.pay(new CreditCardStrategy( “1234567890123456”));

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
} }

o/p:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Paypal : $50 CreditCard : $50

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
