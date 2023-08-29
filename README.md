public class Perfil {

    private final List<String> conocimientos = new ArrayList<>();

    public void saludo() {
        System.out.println("Bienvanido !!");
        System.out.println("Mi nombtre es Juan Camilo Escobar Campuzano");
    }

    private List<String> presentacion(){
        conocimientos.add("Java");
        conocimientos.add("Spring Boot");
        conocimientos.add("Sql");
        conocimientos.add("GitHub");
        
        return conocimientos;
    }
}
