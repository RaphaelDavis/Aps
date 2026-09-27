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
public void setCpf(String cpf) {
		this.cpf = cpf;
	}
	public String getNome() {
		return nome;
	}
	public void setNome(String nome) {
		this.nome = nome;
	}
	public String getEndereco() {
		return endereco;
	}
	public void setEndereco(String endereco) {
		this.endereco = endereco;
	}
	public String getTelefone() {
		return telefone;
	}
	public void setTelefone(String telefone) {
		this.telefone = telefone;
	}
	
	//metodo imprimir 
	public String imprimir(){
		return "CPF: "+cpf+
				"\nNome "+nome+
				"\nEndereco "+endereco+
				"\nTelefone "+telefone+"\n";
	}
	  
}
