package med.voll.api.testes.memoria;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;

import med.voll.api.ApiApplication;
import med.voll.api.domain.paciente.Paciente;

@SpringBootApplication
public class Principal {

	public static void main(String[] args) {
		
		SpringApplication.run(ApiApplication.class, args);
		
		Paciente paciente = new Paciente(null);	
		System.out.println(paciente);
		
		Paciente paciente2 = new Paciente(null);
		System.out.println(paciente == paciente2);
		
		paciente = paciente2;
		System.out.println(paciente == paciente2);
	}

}
	