
        
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
