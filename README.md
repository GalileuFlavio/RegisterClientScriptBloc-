# RegisterClientScriptBloc-
Registrando um bloco Jscript dinamicamente usando o método RegisterClientScriptBloc   

<%@ page Language= "c#" %>

<html>
  <head>
    <script language="C#" runat= "serve"
     public void page_Load(object sender , eventArgs e) {
    
     //Montando o Código script que será registrado np clienete.
     StringBuilder bloco = new ScringBuilder();
     bloco.Append("Script lanquage= javaSript > function cliqueBotao() {"};
     bloco.Append("window.a lert(form.show.valeu + , só .NET salva tua vida! );}");
     bloco.Append("</");
     //poderia tre juntado tudo numa linha só mas, casa
     //eu tivesse feito isso o webmatrix ia confudir essa
     //palavra script com a palavra script do bloco runat=server

     // A função IsClienScriptBlockRegistered verifica se o bloco já foi registrado
     if(!paga.IsClientScriptBlokRegistered("scripteste"))
  }
  </scripr>
</head>
<body tomargin="20" leftmargin="10"
   <fom id="form" runat="serve">
     Digite seu nome:
      <input type="text" id="show" style="width=200">
    </form> 
  </body> 
</html>
