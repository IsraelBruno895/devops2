# devops2
JAVA

```
 public class Arquivo{
    public static void maian(String[] args) throws Exception {
        System.out.println("Ola, Mundo");
        System.out.println("Digite duas notas:");
        double nota1 = JUtil.readDouble();
        double nota2 = JUtil.readDouble();

        double media = nota1 + nota2 / 2;

        System.out.println("media = "+media);

        JUtil.close();
    }
}
```