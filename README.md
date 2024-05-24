# Caua-algoritimo-Brenno
Projeto algoritmo e programação 2


import java.util.Scanner;
class Quiz {

    //Instituição de ensino Alfredo Nascer
    //Caua Martins dos Santos
    //Algoritimos e programação - segundo periodo

    public static void main (String[] args) {
        int numeroAcertos = 0;
        numeroAcertos = numeroAcertos + grupo2();
        System.out.println(" Instituição de ensino Alfredo Nascer");
        System.out.println(" Caua Martins dos Santos");
        System.out.println(" Algoritimos e programação - segundo periodo ");
        System.out.println("Fim do Quiz! perguntas vc acertou: " + numeroAcertos);
    }

    public static int grupo2() {
        int cont = 0;
        String respostaUsuario;
        Questao questao1 = new Questao();
        questao1.pergunta = "Qual esporte Airton Senna foi referencia";
        questao1.opcaoA = "A - futebol";
        questao1.opcaoB = "B - volei";
        questao1.opcaoC = "C - formula 1";
        questao1.opcaoD = "D - tenis";
        questao1.opcaoE = "E - natação";
        questao1.correta = "C";
        questao1.escrevaQuestao();
        respostaUsuario = leiaResposta();
        if (questao1.isCorreta(respostaUsuario)){
            cont++;
        }
        Questao questao2 = new Questao();
        questao2.pergunta = "Qual seleção nacional venceu a Copa do Mundo de Futebol mais vezes?";
        questao2.opcaoA = "A - Brasil";
        questao2.opcaoB = "B - Alemanha";
        questao2.opcaoC = "C - Argentina";
        questao2.opcaoD = "D - Itália";
        questao2.opcaoE = "E - Uruguai ";
        questao2.correta = "A";
        questao2.escrevaQuestao();
        respostaUsuario = leiaResposta();
        if (questao2.isCorreta(respostaUsuario)){
            cont++;
        }
        Questao questao3 = new Questao();
        questao3.pergunta = "Qual clube venceu a UEFA Champions League mais vezes?";
        questao3.opcaoA = "A - Barcelona";
        questao3.opcaoB = "B - Bayern de Munique";
        questao3.opcaoC = "C - Liverpool";
        questao3.opcaoD = "D - AC Milan";
        questao3.opcaoE = "E - Real Madrid";
        questao3.correta = "E";
        questao3.escrevaQuestao();
        respostaUsuario = leiaResposta();
        if (questao3.isCorreta(respostaUsuario)){
            cont++;
        }
        Questao questao4 = new Questao();
        questao4.pergunta = "Qual país sediou a Copa do Mundo de Futebol de 2018?";
        questao4.opcaoA = "A - Alemanha";
        questao4.opcaoB = "B - Rússia";
        questao4.opcaoC = "C - Brasil";
        questao4.opcaoD = "D - França";
        questao4.opcaoE = "E - África do Sul";
        questao4.correta = "B";
        questao4.escrevaQuestao();
        respostaUsuario = leiaResposta();
        if (questao4.isCorreta(respostaUsuario)){
            cont++;
        }
        Questao questao5 = new Questao();
        questao5.pergunta = "Quem é o maior artilheiro da história da Liga dos Campeões da UEFA?";
        questao5.opcaoA = "A - Cristiano Ronaldo";
        questao5.opcaoB = "B - Lionel Messi";
        questao5.opcaoC = "C - Raúl González";
        questao5.opcaoD = "D - Robert Lewandowski";
        questao5.opcaoE = "E - Karim Benzema";
        questao5.correta = "A";
        questao5.escrevaQuestao();
        respostaUsuario = leiaResposta();
        if (questao5.isCorreta(respostaUsuario)){
            cont++;
        }
            Questao questao6 = new Questao();
            questao6.pergunta = "Após o usuário clicar em um link de uma página da Internet, o navegador exibiu a mensagem “Erro 404 – Página não encontrada” porquê:";
            questao6.opcaoA = "A - a conexão de internet está indisponível, pois o link não foi acessado";
            questao6.opcaoB = "B - o buscador não encontrou o termo procurado";
            questao6.opcaoC = "C - o download da página não foi concluído, por isso não foi encontrada";
            questao6.opcaoD = "D - o navegador precisa ser atualizado";
            questao6.opcaoE = "E - o link está errado, pois encaminhou para um endereço indisponível";
            questao6.correta = "E";
            questao6.escrevaQuestao();
            respostaUsuario = leiaResposta();
            if (questao6.isCorreta(respostaUsuario)){
                cont++;
            }
            Questao questao7 = new Questao();
            questao7.pergunta = "Julgue em certo ou errado: Ao comprar um computador, o word, power point e excel já vem instalados.";
            questao7.opcaoA = "A - Certo";
            questao7.opcaoB = "B - Errado";
            questao7.correta = "B";
            questao7.escrevaQuestao();
            respostaUsuario = leiaResposta();
            if (questao7.isCorreta(respostaUsuario)){
                cont++;
            }
            Questao questao8 = new Questao();
            questao8.pergunta = "Quais são os 4 sistemas operacionais para computador que existem?";
            questao8.opcaoA = "A - Windows, Google, Apple e Kaspersky";
            questao8.opcaoB = "B - Kaspersky, Mac, Chrome e Likswet";
            questao8.opcaoC = "C - Windows, Mac, Chrome e Linux";
            questao8.opcaoD = "D - Windows, Mac, Chrome e Kaspesky";
            questao8.correta = "C";
            questao8.escrevaQuestao();
            respostaUsuario = leiaResposta();
            if (questao8.isCorreta(respostaUsuario)){
                cont++;
            }
            Questao questao9 = new Questao();
            questao9.pergunta = "Qual a unidade de armazenamento que vem após o terabyte?";
            questao9.opcaoA = "A - Gigabyte";
            questao9.opcaoB = "B - Tetrabyte";
            questao9.opcaoC = "C - Pentabyte";
            questao9.opcaoD = "D - Magabyte";
            questao9.correta = "C";
            questao9.escrevaQuestao();
            respostaUsuario = leiaResposta();
            if (questao9.isCorreta(respostaUsuario)){
                cont++;
            }
            Questao questao10 = new Questao();
            questao10.pergunta = "Marque a alternativa correta correta a cerca da ferramenta da Microsoft: Exce";
            questao10.opcaoA = "A - É possível conectar a chatbot de whatsapp (LuzIA) a ferramenta, fazendo com que a planilha fique mais dinâmica.";
            questao10.opcaoB = "B - É possível conectar o Excel a uma fonte de dados exterior, assim podendo deixar os dados de uma planilha atualizarem sozinhos.";
            questao10.opcaoC = "C - Ao abrir a ferramenta, é possível realizar contas matemáticas de maneira automática, fazendo com que não precise fazer mais nada a não ser deixar a conta sem conexões.";
            questao10.correta = "B";
            questao10.escrevaQuestao();
            respostaUsuario = leiaResposta();
            if (questao10.isCorreta(respostaUsuario)){
                cont++;
            }
            Questao questao11 = new Questao();
            questao11.pergunta = "Sobre o sistema operacional Linux, assinale a alternativa que apresenta os programas de trabalho-base:";
            questao11.opcaoA = "A - LinxOffice: Writer, Slides e Planes";
            questao11.opcaoB = "B - LibreOffice: Writer, Calc e Impress";
            questao11.opcaoC = "C - Microsoft Office: Word, Excel e PowerPoint";
            questao11.correta = "B";
            questao11.escrevaQuestao();
            respostaUsuario = leiaResposta();
            if (questao11.isCorreta(respostaUsuario)){
                cont++;
            }
            Questao questao12 = new Questao();
            questao12.pergunta = "Julgue a frase: Embora um firewall não seja considerado como uma ferramenta importante na prevenção de invasões e pragas virtuais, ele é um programa que auxilia o usuário quanto à segurança da informação, pois impede que programas em geral sejam instalados no computador por usuário que não seja o administrador do sistema. ”";
            questao12.opcaoA = "A - Correto";
            questao12.opcaoB = "B - Errado";
            questao12.correta = "B";
            questao12.escrevaQuestao();
            respostaUsuario = leiaResposta();
            if (questao12.isCorreta(respostaUsuario)){
                cont++;
            }
            Questao questao13 = new Questao();
            questao13.pergunta = "O que é BIOS?";
            questao13.opcaoA = "A - BIOS é o programa responsável por evitar a queima dos sistemas operacionais e as tarefas mais importantes de um computador, a partir do momento em que ele é ligado.";
            questao13.opcaoB = "B - BIOS é o programa, que pode ser baixado no Google Chrome responsável por iniciar os sistemas operacionais e as tarefas mais importantes de um computador, a partir do momento em que ele é ligado.";
            questao13.opcaoC = "C - BIOS é o programa responsável por iniciar os sistemas operacionais e as tarefas mais importantes de um computador, sendo irrelevante a máquina estar ligada ou não.";
            questao13.opcaoD = "D - BIOS é o programa responsável por iniciar os sistemas operacionais e as tarefas mais importantes de um computador, a partir do momento em que ele é ligado.";
            questao13.correta = "D";
            questao13.escrevaQuestao();
            respostaUsuario = leiaResposta();
            if (questao13.isCorreta(respostaUsuario)){
                cont++;
            }
            Questao questao14 = new Questao();
            questao14.pergunta = "O que é um Worm?";
            questao14.opcaoA = "A - O worm é um tipo de software usado em edições de vídeos.";
            questao14.opcaoB = "B - O worm é um tipo de malware mais perigoso que um vírus comum, o objetivo do malware, em geral, é roubar dados do usuário ou de empresas.";
            questao14.opcaoC = "C - O worm é um tipo de software usado em programação.";
            questao14.opcaoD = "D - O worm é um tipo de malware menos perigoso que um vírus comum, o objetivo do malware, em geral, é apenas checar se o computador está livre de vírus.";
            questao14.correta = "B";
            questao14.escrevaQuestao();
            respostaUsuario = leiaResposta();
            if (questao14.isCorreta(respostaUsuario)){
                cont++;
            }
            Questao questao15 = new Questao();
            questao15.pergunta = "Quando estivermos utilizando o MS-Windows 2010, podemos verificar os aplicativos que estão abertos:";
            questao15.opcaoA = "A - no Painel de Controle";
            questao15.opcaoB = "B - na barra de Ferramentas";
            questao15.opcaoC = "C - no explorador de Arquivos";
            questao15.opcaoD = "D - na barra de Tarefas";
            questao15.correta = "D";
            questao15.escrevaQuestao();
            respostaUsuario = leiaResposta();
            if (questao15.isCorreta(respostaUsuario)){
                cont++;
            }
        Questao questao16 = new Questao();
        questao16.pergunta = "Quando estivermos utilizando o MS-Windows 2010, podemos verificar os aplicativos que estão abertos:";
        questao16.opcaoA = "A - no Painel de Controle";
        questao16.opcaoB = "B - na barra de Ferramentas";
        questao16.opcaoC = "C - no explorador de Arquivos";
        questao16.opcaoD = "D - na barra de Tarefas";
        questao16.correta = "D";
        questao16.escrevaQuestao();
        respostaUsuario = leiaResposta();
        if (questao15.isCorreta(respostaUsuario)) {
            cont++;
        }
            return cont;





        }


        public static String leiaResposta() {
            Scanner ler = new Scanner(System.in);
            String resp;
            do {
                System.out.println("Digite a resposta: ");
                resp = ler.next();
            } while (!respostaValida(resp));
            return resp;
        }

        public static boolean respostaValida(String resp) {
            if (resp.equalsIgnoreCase("A") || resp.equalsIgnoreCase("B") || resp.equalsIgnoreCase("C") ||
                    resp.equalsIgnoreCase("D") || resp.equalsIgnoreCase("E")) {
                return true;
            }
            System.out.println("Resposta inválida ... ");
            return false;
        }
}

class Questao {
    String pergunta = "";
    String opcaoA = "";
    String opcaoB = "";
    String opcaoC = "";
    String opcaoD = "";
    String opcaoE = "";
    String correta = "";

    public boolean isCorreta(String resposta) {
        if (resposta.equalsIgnoreCase(this.correta)) {
            System.out.println("Parabéns resposta Correta! - Letra: " + this.correta);
            return true;
        } else {
            System.out.println("Resposta Errada!");
            System.out.println("A opção correta é a letra: " + this.correta);
            return false;
        }
    }

    public void escrevaQuestao() {
        System.out.println(this.pergunta);
        System.out.println();
        System.out.println(this.opcaoA);
        System.out.println(this.opcaoB);
        System.out.println(this.opcaoC);
        System.out.println(this.opcaoD);
        System.out.println(this.opcaoE);
        System.out.println();

    }
}
