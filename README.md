![CAPA](https://user-images.githubusercontent.com/70676418/119589714-c65c6a00-bda9-11eb-8c8e-2cb3a86fc6fb.jpg)

        
        public class Human {
                String name;
                Integer age;  
                String country;
                String state;
                String city;
                String description;
  
                public Human() {
  
                }
  
                public Human(String name , Integer age , String country , String state , String city) {
                        this.name = name;
                        this.age = age;
                        this.country = country;
                        this.state = state;
                        this.city = city;
                        description = "Make your own story";
                }
        }

        public static void main(String[] args) {
                String name = "Luiz Eduardo Vieira Barreto";
                Integer age = 18;
                String country = "Brazil";
                String state = "Paraná";
                String city = "Boa Esperança"

                Human human = new Human(name , age , country , state , city);
        }
