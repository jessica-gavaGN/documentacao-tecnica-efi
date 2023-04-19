<div>
<div className="espaco-1">

#### Dados para envio de Pix.
<div className="light">
(*) são atributos obrigatórios
</div>
</div>
<br/>

****

  <div className="atributo"> 
          <div className="col-77">
           <b>idEnvio (Identificador da transação)</b>   
          </div>
          <div className="col-23">
            <div className="obrigatorio">
              <svg id="check-circle" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
  <path id="Caminho_19146" data-name="Caminho 19146" d="M127.946,200a8,8,0,1,0,8,8A7.936,7.936,0,0,0,127.946,200Zm0,15.2a7.2,7.2,0,0,1-5.09-12.29,7.131,7.131,0,0,1,5.09-2.11,7.2,7.2,0,0,1,0,14.4Z" transform="translate(-119.946 -200)" fill="#2f2f2f"/>
  <path id="Caminho_19147" data-name="Caminho 19147" d="M127.964,211.4l-2.4-2.4a.4.4,0,0,1,.564-.565l2.115,2.115,4.234-4.234a.4.4,0,1,1,.569.57l-4.518,4.514a.393.393,0,0,1-.564,0Z" transform="translate(-121.046 -201.241)" fill="#2f2f2f"/>
</svg> 
               <b>Obrigatório</b>      
            </div>
          </div>
  </div>                                      

<div className="light"> 

string (Id da Transação) ``^[a-zA-Z0-9]{1,35}$``
</div>
<br/>
O campo idEnvio determina o identificador da transação.

****

 <div className="atributo"> 
          <div className="col-77">
           <b>valor</b>   
          </div>
          <div className="col-23">
           <div className="obrigatorio">
             <svg id="check-circle" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
  <path id="Caminho_19146" data-name="Caminho 19146" d="M127.946,200a8,8,0,1,0,8,8A7.936,7.936,0,0,0,127.946,200Zm0,15.2a7.2,7.2,0,0,1-5.09-12.29,7.131,7.131,0,0,1,5.09-2.11,7.2,7.2,0,0,1,0,14.4Z" transform="translate(-119.946 -200)" fill="#2f2f2f"/>
  <path id="Caminho_19147" data-name="Caminho 19147" d="M127.964,211.4l-2.4-2.4a.4.4,0,0,1,.564-.565l2.115,2.115,4.234-4.234a.4.4,0,1,1,.569.57l-4.518,4.514a.393.393,0,0,1-.564,0Z" transform="translate(-121.046 -201.241)" fill="#2f2f2f"/>
</svg> 
              <b>Obrigatório</b>   
            </div>
          </div>
  </div>  

<div className="light"> 

string ``\d{1,10}\.\d{2}``
</div>
<br/>
Valores monetários referentes à cobrança.

****
 <div className="atributo"> 
          <div className="col-77">
           <b>pagador</b>   
          </div>
          <div className="col-23">
           <div className="obrigatorio">
             <svg id="check-circle" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
  <path id="Caminho_19146" data-name="Caminho 19146" d="M127.946,200a8,8,0,1,0,8,8A7.936,7.936,0,0,0,127.946,200Zm0,15.2a7.2,7.2,0,0,1-5.09-12.29,7.131,7.131,0,0,1,5.09-2.11,7.2,7.2,0,0,1,0,14.4Z" transform="translate(-119.946 -200)" fill="#2f2f2f"/>
  <path id="Caminho_19147" data-name="Caminho 19147" d="M127.964,211.4l-2.4-2.4a.4.4,0,0,1,.564-.565l2.115,2.115,4.234-4.234a.4.4,0,1,1,.569.57l-4.518,4.514a.393.393,0,0,1-.564,0Z" transform="translate(-121.046 -201.241)" fill="#2f2f2f"/>
</svg> 
              <b>Obrigatório</b>   
            </div>
          </div>
  </div>                                           

<div className="light"> 
Pessoa Física (object) or Pessoa Jurídica (object)
</div>
<br/>
O campo pagador contém a chave Pix associada a conta autenticada que será debitado o valor definido.
<br/>
<br/><br/> <div>
pagador:
</div>

``chave*`` - O campo chave determina a chave Pix registrada no DICT que será utilizada identificar o pagador do Pix.
string (Chave DICT do pagador) ≤ 77 characters

``infoPagador`` -Informação do pagador sobre o Pix a ser enviado. string  < 140


****

<div className="atributo"> 
          <div className="col-77">
           <b>favorecido</b>   
          </div>
          <div className="col-23">
           <div className="obrigatorio">
             <svg id="check-circle" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
  <path id="Caminho_19146" data-name="Caminho 19146" d="M127.946,200a8,8,0,1,0,8,8A7.936,7.936,0,0,0,127.946,200Zm0,15.2a7.2,7.2,0,0,1-5.09-12.29,7.131,7.131,0,0,1,5.09-2.11,7.2,7.2,0,0,1,0,14.4Z" transform="translate(-119.946 -200)" fill="#2f2f2f"/>
  <path id="Caminho_19147" data-name="Caminho 19147" d="M127.964,211.4l-2.4-2.4a.4.4,0,0,1,.564-.565l2.115,2.115,4.234-4.234a.4.4,0,1,1,.569.57l-4.518,4.514a.393.393,0,0,1-.564,0Z" transform="translate(-121.046 -201.241)" fill="#2f2f2f"/>
</svg> 
              <b>Obrigatório</b>   
            </div>
          </div>
  </div>                                                  

<div className="light"> 
object
</div>
<br/>
O campo favorecido contém a chave Pix que será creditado o valor definido.
<br/> <div>
Atributos favorecido:

</div>

``chave`` - O campo chave determina a chave Pix registrada no DICT que será utilizada identificar o recebedor do Pix. string (Chave DICT do recebedor) ``≤ 77 characters``

<br/>
<br/> <div>
Atributos chave:
</div>

``cpf`` - O campo cpf valida se a chave Pix registrada no DICT pertence ao titular do documento informado

``cnpj`` - O campo cnpj valida se a chave Pix registrada no DICT pertence ao titular do documento informado


Obs: Os atributos cpf e cnpj são opcionais, mas uma vez inseridos no schema, o preenchimento passa a ser obrigatório.

<br/>
<br/> <div>
Atributos contaBanco:
</div>

``nome*`` - Nome do recebedor (string) ``< 200 characters``

``cpf`` - CPF do recebedor (string) ``^[0-9]{11}$``

``cnpj`` - CNPJ do recebedor (string) ``^[0-9]{14}$``

``codigoBanco*`` - <a href="https://www.bcb.gov.br/pom/spb/estatistica/port/ASTR003.pdf">ISPB do Banco do recebedor</a> (string) ``^[0-9]{8}$``

``agencia*`` - Agência do recebedor no seu Banco, sem o dígito verificador (string) ``^[0-9]{1,4}$``

``conta*`` - Conta do recebedor no seu Banco com o dígito verificador, sem traço - (string) ``^[0-9]+``

``tipoConta*`` - Tipo da conta do recebedor no seu Banco (string) ``^[0-9]+``, podendo ser: ``cacc`` (Conta corrente) ou ``svgs`` (poupança)

****
<div className="atributo"> 
          <div className="col-80">
           <b>status</b>   
          </div>
          <div className="col-20">
           <div className="opcional">
            <svg id="minus-circle" xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 16 16">
  <path id="Caminho_19359" data-name="Caminho 19359" d="M728,200a8,8,0,1,0,8,8A8.009,8.009,0,0,0,728,200Zm0,15.2a7.2,7.2,0,1,1,7.2-7.2A7.208,7.208,0,0,1,728,215.2Z" transform="translate(-720 -200)" fill="#2f2f2f"/>
  <path id="Caminho_19360" data-name="Caminho 19360" d="M732.541,209.5H725.5a.4.4,0,1,0,0,.8h7.043a.4.4,0,0,0,0-.8Z" transform="translate(-721.02 -201.9)" fill="#2f2f2f"/>
</svg> 
              <b>Opcional</b>   
            </div>             
            </div>
          </div>
  </div>     

<div className="light"> 

string 
</div> 
<br/>
O campo status no retorno do webhook representa a situação da requisição de envio direto de um Pix para uma chave Pix, podendo assumir os seguintes estados:

``"EM_PROCESSAMENTO"``,``"REALIZADO"``, ``"NAO_REALIZADO"``




</div>
 

