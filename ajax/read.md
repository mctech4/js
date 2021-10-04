 /*{
    url:url,
    method:method => 'GET', 'POST', 'PUT', 'DELETE' default to GET method
    header:header=>
    type:type, =>'json','text','html', 'xml', default=html,
    load:function(res){} => response data
    data:formdata => in string => "key=value&key1=value2" in object => {key:"value", key2:"value2"}
  }
  */