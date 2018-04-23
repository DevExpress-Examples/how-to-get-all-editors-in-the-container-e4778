# How to get all editors in the container


<p>To achieve this, we first create a Selector class, which uses <a href="http://msdn.microsoft.com/en-us/library/ms379564(v=vs.80).aspx"><u>C# Generics</u></a> for more flexibility. The base class is defined via the 

```cs
where T : Control
```

 constraint.</p><p>This class has one public static method. It accepts any type of control and recursively counts the total number of controls in a container specified as a parameter.</p><p><br />
In the markup we have some controls arranged in two panels. We also have an ASPxButton, which starts the counting process and an ASPxPopupControl to show the results.</p>

<br/>

