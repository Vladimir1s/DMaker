s. www.diseasemapper.de

enum Type {
		Disease,
		Chemie;
	}


		
		String url = "http://www.diseasemapper.de:8080/dsmap/plain?item=" + type + "&id=" + name;
   
  f.e. 
  
		Type type = Type.Disease;
		String name = "aaa";
    
    http://localhost:8080/DMaker/plain?item=Disease&searchTextName=aaa
    
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
