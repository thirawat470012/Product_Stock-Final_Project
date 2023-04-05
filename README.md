# ความเป็นมาของโปรแกรม

ต้องการทำโปรแกรมสต๊อกสินค้าเพื่อจัดการระบบสินค้าง่ายๆ

# วัตถุประสงค์ของโปรแกรม

บันทึกสินค้าเพื่อให้ง่ายต่อการจัดการ

# ชื่อผู้พัฒนาโปรแกรม

นายถิรวัฒน์ โชติธนกิจไพศาล 653450090-6

# classDiagram
classDiagram
ResourceInfo --|> Resource 
<<Interface>> ResourceInfo
Resource --|> ResourceInfo
note for Resource "Add Product" 
ClassProdouct --> Resource
ClassProdouct : str name
ClassProdouct : str category
ClassProdouct : int Number
ClassProdouct --|> ResourceInfo
ResourceInfo : DataGirds()
ResourceInfo : +NewItem()



 
