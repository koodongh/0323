



```
//	public Book() {};
//	
//	public Book(String isbn, String title, String author, String publisher, int price, String desc) {
//		super();
//		this.isbn = isbn;
//		this.title = title;
//		this.author = author;
//		this.publisher = publisher;
//		this.price = price;
//		this.desc = desc;
//	}

```

```
"21424", "Java Pro", "김하나", "Jaen.kr", 15000,"기본문법" 
"35355", "OOAD 분석,설계", "소나무", "Jaen.kr", 30000,"" 
"35535", "Java World", "편집부", "androidjava.com", 7000,2013,2,"" 
```



```
		a.isbn = "21424";
		a.title = "Java Pro";
		a.author = "김하나";
		a.publisher = "Jaen.kr";
		a.price = 15000;
		a.desc = "기본문법";
				
		Book b = new Book();
		
		
		b.isbn = "35355";
		b.title = "OOAD 분석,설계";
		b.author = "소나무";
		b.publisher = "Jaen.kr";
		b.price = 30000;
		b.desc = "";
		
		
		Magazine c = new Magazine();
		
		c.isbn = "35535";
		c.title = "Java World";
		c.author = "편집부";
		c.publisher = "androidjava.com";
		c.price = 7000;
		c.year = 2013;
		c.month = 2;
		c.desc = "";
		
		System.out.println(a);
		System.out.println(b);
		System.out.println(c);
```

