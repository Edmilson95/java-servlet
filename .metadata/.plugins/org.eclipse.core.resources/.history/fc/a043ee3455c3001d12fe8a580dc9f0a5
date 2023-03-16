package br.com.alura.gerenciador.acao;

import java.io.IOException;

import javax.servlet.ServletException;
import javax.servlet.http.HttpServletRequest;
import javax.servlet.http.HttpServletResponse;

public class NovaEmpresaForm {

	public String executa(HttpServletRequest request, HttpServletResponse response)
			throws ServletException, IOException {

		return "forward:formNovaEmpresa.jsp";

	}

}

class Veiculo {

	public void acelerar() {

		System.out.println("Veiculo acelerando");

	}

}

class Carro extends Veiculo {

	public void acelerar() {

		System.out.println("Carro acelerando");

	}

}

class Teste {

	public static void main(String[] args) {

		Veiculo veiculo = new Carro();

		veiculo.acelerar();
	}

}
