#SDK Olho Vivo PHP

Uma abstração em PHP para a [API do Olho Vivo][1] com todos os métodos disponibilizados pela versão 0 (zero)

##Métodos

### URL de acesso
> http://api.olhovivo.sptrans.com.br/v0
### Autenticação
> POST /Login/Autenticar?token={token}
### Linhas
> GET /Linha/Buscar?termosBusca={termosBusca} 

### Paradas
> GET /Linha/CarregarDetalhes?codigoLinha={codigoLinha} 

### Corredores
> GET /Parada/Buscar?termosBusca={termosBusca} 

### Posição dos veículos
> GET /Parada/BuscarParadasPorLinha?codigoLinha={codigoLinha} 

### Previsão de chegada
> GET /Parada/BuscarParadasPorCorredor?codigoCorredor={codigoCorredor} 


[1]: http://www.sptrans.com.br/desenvolvedores/
