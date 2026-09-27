package aps;

import java.util.ArrayList;
import javax.swing.JOptionPane;

public class Conta {

	private int numero;
	private double saldo=0;
	private double quantia=0;
	private Cliente end;
	private static ArrayList<Conta> list = new ArrayList();
	
//contrutor default
	public Conta() {}
	
	//sobrecarga do contrutor
	

        public Conta(int numero, Cliente end) {
            this.numero = numero;
            this.end = end;
        }
	
	//gets e sets
	public void setNumero(int numero) {
		this.numero=numero;
	}
	
	public int getNumero() {
		return numero;
	}
	
	public double getSaldo() {
		return saldo;
	}

	public void setSaldo(double saldo) {
		this.saldo = saldo;
	}
	
	public double getQuantia() {
		return quantia;
	}

	public void setQuantia(double quantia) {
		this.quantia = quantia;
	}
	
	public Cliente getEnd() {
		return end;
	}

	public void setEnd(Cliente end) {
		this.end = end;
	}
	
	//metodo depositar
	public void depositar(double quantia) {
		saldo = saldo+quantia;
	
        }
        
