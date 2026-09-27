public class Cliente{
  private String cpf = new String();
  private String nome = new String();
  private String endereco = new String();
  private String telefone = new String();

  //construtor default
  public Cliente()  {}

  // sobrecarga do construtor
  public Cliente (String cpf, String nome, String enderreco,String telefone){
              this.cpf=cpf;
              this.nome=nomee;
              this.endereco=endereco;
              this.telefone=telefone;
  }

  //gets and sets
  pubiic String getCpf(){
      return cpf;
  }


  
  
}
