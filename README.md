import java.util.List;

public class Main {

    public static void main(String[] args) {
        Perfil miPerfil = new Perfil();
        miPerfil.saludo();
        
        List<String> listaConocimientos = miPerfil.presentacion();
        System.out.println("Mis conocimientos son:");
        for (String conocimiento : listaConocimientos) {
            System.out.println("- " + conocimiento);
        }
    }
}

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
        conocimientos.add("Angular");
        conocimientos.add("Html");
        conocimientos.add("Css");
        conocimientos.add("Aws");
        conocimientos.add("Devops");
        
        return conocimientos;
    }
}
