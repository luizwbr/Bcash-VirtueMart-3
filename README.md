# Bcash-VirtueMart-3
Método de pagamento não-oficial que integra o Bcash com o VirtueMart, redirecionando os clientes para o ambiente do Bcash.
* Virtuemart 3.x / Joomla 3.x

Tutorial
----------

Passo 1 - Habilite o plugin Administrar Plugins
Passo 2 - Instale Plugin por esta tela Métodos de pagamento
Passo 2.1 - Clique em Novo Método de Pagamento e preencha as informações:
* Nome do Pagamento: Bcash
* Publicado: Sim
* Descrição do pagamento: Pague com Bcash
* Método de pagamento: Bcash
* Grupo de Compradores: nenhum
Passo 2.2 - Clique em Salvar.
Passo 3 - Na aba configurações, preencha os dados:
* Logotipos:
* Email de Configuração da loja: Email da conta no Bcash
* Chave da Loja: Menu Ferramentas do Bcash
* Chave Única de Acesso da Loja: Menu Ferramentas do Bcash
* Limite de Parcelamento: Por padrão é 24
* Campo CPF ( Deve ser criado caso não exista )
* Campo CNPJ ( Deve ser criado caso não exista )
* Campo Razão Social ( Deve ser criado caso não exista )
* Campo Bairro ( Deve ser criado caso não exista )
* Campo Número ( Deve ser criado caso não exista )
* Aprovado: Status do Pedido quando Aprovada a transação
* Cancelado: Status do Pedido quando Cancelada a transação
* Aguardando Pagto: Status do Pedido quando transação Pendente

Licença
-------

Copyright 2015 Weber TI.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.


Dúvidas?
----------

Em caso de dúvidas acesse o site http://virtuemartpro.com.br.

Contato
----------

Luiz Felipe Weber
weber@weber.eti.br

Contribuições
-------------

Achou e corrigiu um bug ou tem alguma feature em mente e deseja contribuir?

* Faça um fork
* Adicione sua feature ou correção de bug (git checkout -b my-new-feature)
* Commit suas mudanças (git commit -am 'Added some feature')
* Rode um push para o branch (git push origin my-new-feature)
* Envie um Pull Request
* Obs.: Adicione exemplos para sua nova feature. Se seu Pull Request for relacionado a uma versão específica, o Pull Request não deve ser enviado para o branch master e sim para o branch correspondente a versão.
