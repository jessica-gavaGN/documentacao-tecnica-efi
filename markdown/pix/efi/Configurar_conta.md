<div>
<div className="espaco-1">

#### Dados para configuração da conta
<div className="light">
(*) são atributos obrigatórios
</div>
</div>
<br/>

****
 <div className="atributo"> 
          <div className="col-77">
           <b>pix</b>   
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
Object 
</div>

<br/><br/> <div>
Objeto contendo as configurações da conta relacionadas ao Pix.
</div>

``receberSemChave*`` - Atributo booleano obrigatório que configura a possibilidade do recebimento de Pix sem chaves cadastradas.

``chaves`` - Atributo objeto opcional. Pode conter uma ou mais chaves e suas configurações individuais.

``<chave pix>`` - Atributo string opcional. String que representa uma chave Pix e satisfaz à Regex ``^[a-zA-Z0-9-.@_+]{1,77}$``

``recebimento*`` - Atributo objeto obrigatório. Contém as configurações relacionadas aos recebimentos de Pix por uma determinada chave.

``txidObrigatorio*`` - Atributo booleano obrigatório. Configura a obrigatoriedade de txid nas cobranças recebidas por uma chave Pix.

``qrCodeEstatico*`` - Atributo objeto obrigatório. Contém as configurações relacionadas à QR Codes estáticos para uma determinada chave Pix.

``recusarTodos*`` - Atributo booleano obrigatório. Configura a rejeição de todos os QR Codes estáticos.

``webhook`` - Atributo objeto opcional. Contém as configurações relacionadas aos recebimentos de informação das tarifas por cada cobrança Pix recebida ou enviada.

``tarifa*`` - Atributo booleano obrigatório. Configura o recebimento ou não do valor das tarifas pagas ao receber ou enviar Pix na conta Efí.

</div>
 

