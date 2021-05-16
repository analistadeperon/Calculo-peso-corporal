# Calculo-peso-corporal

<div id="app"></div>

<html>
<head><meta charset="UTF-8"></head>
<form action="http://formmail.kinghost.net/formmail.cgi" method="POST"> 
 <input type="hidden" name="recipient" value="testeiseuemail@gmail.com"> <!-- Pode ser qualquer endereço de email -->
 <input type="hidden" name="redirect" value="http://seudominio"> <!-- Após o envio, o usuário será redirecionado para a página configurada aqui -->
 <input type="hidden" name="subject" value="teste de assunto">  <!-- Assunto da mensagem -->
 <input type="hidden" name="email" value="email@doseudominio">   <!-- Deve ser uma conta de email ativa em seu domínio -->
 
 <p> 
 Nome:<br /> 
 <input type="text" size="30" name="nome"> 
 </p>   
 
 <p>
 E-mail:<br /> 
 <input type="text" size="30" name="replyto"> 
 </p>   
 
 <p> 
 Comentários:<br /> 
 <input type="text" size="35" name="Comentarios"> 
 </p>   
 
 <p> 
 <input type="submit" name="BTEnvia" value="Enviar"> 
 <input type="reset" name="BTApaga" value="Apagar"> </p> 
 </form>
 
</html> 
<form action="#" method="post">
    <fieldset>
        <fieldset class="grupo">
            <div class="campo">
                <label for="nome">Nome</label>
                <input type="text" id="nome" name="nome" style="width: 10em" value="">
            </div>
            <div class="campo">
                <label for="snome">Sobrenome</label>
                <input type="text" id="snome" name="snome" style="width: 10em" value="">
            </div>
        </fieldset>
        <div class="campo">
            <label>Sexo</label>
            <label>
                <input type="radio" name="sexo" value="masculino"> Masculino
            </label>
            <label>
                <input type="radio" name="sexo" value="feminino"> Feminino
            </label>
        </div>
        <div class="campo">
            <label for="email">E-mail</label>
            <input type="text" id="email" name="email" style="width: 20em" value="">
        </div>
        <div class="campo">
            <label for="telefone">Telefone</label>
            <input type="text" id="telefone" name="telefone" style="width: 10em" value="">
        </div>

        <fieldset class="grupo">
            <div class="campo">
                <label for="cidade">Cidade</label>
                <input type="text" id="cidade" name="cidade" style="width: 10em" value="">
            </div>
            <div class="campo">
                <label for="estado">Estado</label>
                <select name="estado" id="estado">
                    <option value="">--</option>
                    <option value="PR">PR</option>
                </select>
            </div>
        </fieldset>

        <div class="campo">
            <label for="mensagem">Mensagem</label>
            <textarea rows="6" style="width: 20em" id="mensagem" name="mensagem"></textarea>
        </div>

        <div class="campo">
            <label>Newsletter</label>
            <label>
                <input type="checkbox" name="newsletter" value="1"> Gostaria de receber a Newsletter da empresa
            </label>
        </div>

        <button type="submit" name="submit">Enviar</button>
    </fieldset>
</form>
<html>
<CENTER>
<FORM NAME="Calc">
<TABLE BORDER=4 WIDTH="155" bgcolor="green">
	<TR>
		<TD ALIGN="CENTER">
			<INPUT TYPE="text"  NAME="Input" SIZE="16">
		</TD>
	</TR>
	<TR>
		<TD ALIGN="CENTER">
			<INPUT TYPE="button" NAME="one"
			VALUE="  1  " onClick="Calc.Input.value += '1'">
			<INPUT TYPE="button" NAME="two"
			VALUE="  2  " onClick="Calc.Input.value += '2'">
			<INPUT TYPE="button" NAME="three"
			VALUE="  3  " onClick="Calc.Input.value += '3'">
			<INPUT TYPE="button" NAME="plus"
			VALUE="  +  " onClick="Calc.Input.value += ' + '">
			<BR>
			<INPUT TYPE="button" NAME="four"
			 VALUE="  4  " onClick="Calc.Input.value += '4'">
			 <INPUT TYPE="button" NAME="five"
			 VALUE="  5  " onClick="Calc.Input.value += '5'">
			 <INPUT TYPE="button" NAME="six"
			 VALUE="  6  " onClick="Calc.Input.value += '6'">
			 <INPUT TYPE="button" NAME="minus"
			 VALUE="  -   " onClick="Calc.Input.value += ' - '">
			<BR>
			 <INPUT TYPE="button" NAME="seven"
			 VALUE="  7  " onClick="Calc.Input.value += '7'">
			 <INPUT TYPE="button" NAME="eight"
			 VALUE="  8  " onClick="Calc.Input.value += '8'">
			 <INPUT TYPE="button" NAME="nine"
			 VALUE="  9  " onClick="Calc.Input.value += '9'">
			 <INPUT TYPE="button" NAME="times"
			 VALUE="  x  " onClick="Calc.Input.value += ' * '">
			<BR>
			<INPUT TYPE="button" NAME="clear"
			 VALUE="  c  " onClick="Calc.Input.value = ''">
			 <INPUT TYPE="button" NAME="zero"
			 VALUE="  0  " onClick="Calc.Input.value += '0'">
			 <INPUT TYPE="button" NAME="DoIt"
			 VALUE="  =  " onClick="Calc.Input.value = eval(Calc.Input.value)">
			 <INPUT TYPE="button" NAME="div"
			 VALUE="  /   " onClick="Calc.Input.value += ' / '">
		</TD>
	</TR>
</TABLE>
</FORM>
</CENTER>
</html>


<div class="yz-widget" data-calculator-type="bmi" data-language="pt" data-unit-system="metric" data-background-color="#EEEEEE" data-text-color="#212121" data-primary-color="#03A9F4" data-alternate-background-color="#FFFFFF" data-alternate-text-color="#FFFFFF" data-secondary-color="#FFC107"><span class="yz-copyright">Powered by <a href="https://www.yazio.com/pt/calculadora-imc">YAZIO</a></span></div>
<script src="https://widget.yazio.com/calculator.js" async></script>
<div class="yz-widget" data-calculator-type="ideal_weight" data-language="pt" data-unit-system="metric" data-background-color="#EEEEEE" data-text-color="#212121" data-primary-color="#03A9F4" data-alternate-background-color="#FFFFFF" data-alternate-text-color="#FFFFFF" data-secondary-color="#FFC107"><span class="yz-copyright">Powered by <a href="https://www.yazio.com/pt/calculadora-peso-ideal">YAZIO</a></span></div>
<script src="https://widget.yazio.com/calculator.js" async></script>
<div class="yz-widget" data-calculator-type="daily_need" data-language="pt" data-unit-system="metric" data-background-color="#EEEEEE" data-text-color="#212121" data-primary-color="#03A9F4" data-alternate-background-color="#FFFFFF" data-alternate-text-color="#FFFFFF" data-secondary-color="#FFC107"><span class="yz-copyright">Powered by <a href="https://www.yazio.com/pt/calculadora-calorias-diarias">YAZIO</a></span></div>
<script src="https://widget.yazio.com/calculator.js" async></script>
<div class="yz-widget" data-calculator-type="calories_burned" data-language="pt" data-unit-system="metric" data-background-color="#EEEEEE" data-text-color="#212121" data-primary-color="#03A9F4" data-alternate-background-color="#FFFFFF" data-alternate-text-color="#FFFFFF" data-secondary-color="#FFC107"><span class="yz-copyright">Powered by <a href="https://www.yazio.com/pt/calculadora-gasto-calorico">YAZIO</a></span></div>
<script src="https://widget.yazio.com/calculator.js" async></script><div class="yz-widget" data-calculator-type="calories_burned" data-language="pt" data-unit-system="metric" data-background-color="#EEEEEE" data-text-color="#212121" data-primary-color="#03A9F4" data-alternate-background-color="#FFFFFF" data-alternate-text-color="#FFFFFF" data-secondary-color="#FFC107"><span class="yz-copyright">Powered by <a href="https://www.yazio.com/pt/calculadora-gasto-calorico">YAZIO</a></span></div>
<script src="https://widget.yazio.com/calculator.js" async></script>
