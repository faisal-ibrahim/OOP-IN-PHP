# OOP-IN-PHP
// Define Two Interface 
/* An Interface is like a template similar to abstract class
with a difference where it uses only abstract methods.

In simple words, an interface is like a class using
interface keyword and contains only function
declarations(function with no body).

An Interface should be implemented in the class and all the
methods or functions should be overridden in this class.

interfaces are used to implement multiple inheritance.because PHP does not support multiple inheritance.
------------------------------------------------------------------
Abstract Classes
An abstract class is like a normal class, except that you cannot instantiate them, you must extend them first then instantiate.
 Your abstract classes can have data members and function calls (and their functionality).
------------------------------------------------------------------ 
 What is Encapsulation?

In single word, encapsulation means, visibility. It refers to visibility of methods or properties of a class.  In general, how would you 
like to make visual of your variable or function in procedural coding. 
3 key words like public, private and protected we use to decide that whether our methods or properties are going to use child class or within class.

Why use Encapsulation?

Sometimes, it is needed to make sure that properties are only usable in own class. In this case, we have to use encapsulation prefix. 
Let’s consider a class where we have to store users name, social security id and how much tax he or she have to pay. In this situation,
 we use following key words for visibility.
 Example:
 class Encap
{
	
	 [$name Store name of the users. It is public and can be called in same class as well as child class]
	 @var String
	
	public $name;
 
	
	[$id Keep social security numbers that are private. Only call in same class]
	 @var Integer
	
	private $id;

	[$tax It is protected and only used on child class ]
	@var Float
	 
	protected $tax;
 
}
Public – The method is publicly available and can be accessed by all subclasses.
Protected – the method / function / property is available to the parent class and all inheriting classes or we call them subclasses or child classes.
Private – the method is private and only available to the parent class / base class.
--------------------------------------------------
What is polymorphism in Object Oriented Programming (OOP)?

- Polymorphism means one name many forms.
- One function behaves different forms.
- In other words, “Many forms of a single object is called Polymorphism.”
*/
