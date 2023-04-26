# visualbasic
visual basic .net 的使用


使用 CLI 创建项目，那么命令是

```
  dotnet new --language VB

```

下面是显示可用于帮助创建项目的模板列表的命令

```

  dotnet new list

```



用于运行 Visual Basic 项目的命令


```

  dotnet run

```

我正在关注这里的教程 [**教程**](https://www.thecodingguys.net/tutorials/visualbasic/vb-variables)



它是在控制台中显示文本的基本源代码

```vb

Imports System

Module File1

	Sub Main(args As String())
	
		Console.WriteLine("Membuat Aplikasi Console Menggunakan Notepad++")
		
	End Sub

End Module

```



它是在控制台中显示数字的源代码

```vb

Imports System

Module File2


	Sub Main()
	
		Dim angka1 as integer
		
		angka1 = 10
		
		
		Console.writeline(angka1)
		
		Console.readline()
	
	
	End Sub
	
	
End Module



```


它是在控制台中以字符串类型显示变量内容的源代码

```vb

Imports system

Module File3

	Sub Main()
	
	 dim nama as string
	 
	 nama = "steven"
	 
	 console.writeline(nama)
	 
	 console.readline()
	
	
	End Sub

End Module

```


它是显示算术运算之一的源代码

这是加法


```vb

Imports system

Module File4

	Sub Main()
	
	
	dim x as integer
	
	dim y as integer
	
	
		x = 20
		y = 25
		
		
		console.writeline(x + y)
		
		console.readline()
	
	End Sub
	
End Module


```


显示构成语句的两个变量内容的源码


```vb

Imports system

Module File5


	Sub Main()
	
		dim tulisan as string
		
		dim nama as string
		
		nama = "Steven"
		
		tulisan = "Nama : " & nama


		Console.WriteLine(tulisan)
		
		Console.ReadLine()
	
	
	
	End sub

End Module


```





