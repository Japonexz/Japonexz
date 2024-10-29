### 1. **Estruturas Básicas**
   - `public class`: Declaração de uma classe.
   - `public static void main(String[] args)`: Método principal.

### 2. **Controle de Fluxo** (VARIAVEIS)
   - `if`, `else if`, `else`: Estruturas condicionais.    
   - `switch`: Estrutura de seleção múltipla.
   - `for`, `while`, `do while`: Laços de repetição.

### 3. **Manipulação de Objetos**
   - `new`: Instancia um novo objeto.
   - `.get()`, `.set()`: Métodos para acessar e modificar atributos de objetos.

### 4. **Estruturas de Dados**
   - `ArrayList<T>`: Lista dinâmica.
   - `HashMap<K,V>`: Estrutura de mapa chave-valor.

### 5. **Entrada/Saída**
   - `System.out.println()`: Impressão no console.
   - `Scanner`: Para leitura de entrada do usuário.

### 6. **Programação Orientada a Objetos**
   - `extends`: Herança de classes.
   - `implements`: Implementação de interfaces.
   - `@Override`: Anotação para sobrescrita de métodos.

### 7. **Conceitos Específicos do FTC**
   - `OpMode`: Classe base para modos de operação.
   - `telemetry`: Usado para enviar dados para o driver station.
   - `hardwareMap`: Mapeia os dispositivos de hardware.

### 8. **Controle de Motores**
   - `DcMotor motor = hardwareMap.get(DcMotor.class, "motorName")`: Mapeia um motor.
   - `motor.setPower(power)`: Define a potência do motor.

### 9. **Sensores**
   - `ColorSensor`, `DistanceSensor`, etc.: Classes para manipular sensores.
   - `sensor.getDistance()`: Método para obter a distância medida.

### 10. **Eventos e Ciclos de Execução**
   - `waitForStart()`: Aguarda o início da operação.
   - `while (opModeIsActive())`: Laço principal que mantém a operação ativa.

### 11. **Bibliotecas e Dependências**
   - `import com.qualcomm.robotcore.*`: Importação de bibliotecas necessárias do FTC.

### 12. **Depuração e Telemetria**
   - `telemetry.addData("Label", data)`: Adiciona dados à telemetria.
   - `telemetry.update()`: Atualiza as informações na tela.
