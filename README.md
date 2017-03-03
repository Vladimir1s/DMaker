s. www.diseasemapper.de

enum Type {
		Disease,
		Chemie;
	}


		
		String url = "http://www.diseasemapper.de:8080/dsmap/plain?item=" + type + "&id=" + name;
   
  f.e. 
  
1. http://www.diseasemapper.de:8080/DMaker/plain?item=Disease&searchTextName=aaa    
    
    result:
    
 <ul>
  <li>
     <a href="http://www.diseasemapper.de:8080/DMaker/plain?Disease=ABDOMINAL AORTIC ANEURYSM">ABDOMINAL AORTIC ANEURYSM</a>
  </li>
  <li>
     <a href="http://www.diseasemapper.de:8080/DMaker/plain?Disease=G30">Alzheimer Disease</a>
  </li>
  <li>
     <a href="http://www.diseasemapper.de:8080/DMaker/plain?Disease=H00257">Achalasia-Addisonianism-Alacrima Synrrome</a>
  </li>
 </ul>
 
2.http://diseasemapper.de:8080/dsmap/plain?itm=D&id=G3
    
    result:
    
 <table>
<Name>
<list>
<item><a href="http://diseasemapper.de:8080/dsmap/plain?itm=D&id=G30">Alzheimer Disease</a><br/></item></list>
</Name>
...
<DBase>
<list>
...
<item>
<icd10>
<list>
    <item><a href="http://apps.who.int/classifications/icd10/browse/2010/en#/G30" target="_blank">G30</a></item>
 </list>
</icd10>
</item>
...
</list>
</DBase>
</table>

 
 
