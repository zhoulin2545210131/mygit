readme,hhh,第一次，哈哈，版本修改
git add sdsada
public void process(Message message){

	ObjectMapper objectMapper = new ObjectMapper();
	Map result = objectMapper.readValue(new String(message.getBody()),Map.class);
	System.out.println(result.toString());
}