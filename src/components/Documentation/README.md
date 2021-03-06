# Componente - gumgaDocumentation

### Uso
```
<gumga-documentation key="{{ keyVariable }}" can-edit="Boolean" api-url="{{ foo.methods.getDocumentationUrl() }}" modal-title="Title for modal" confirm-button="Salvar" confirmButtonClass="btn btn-info">

</gumga-documentation>
```
### Descrição

O componente gumgaDocumentation pode ser utilizado para adicionar documentações que estão cadastradas como softwareValues no Segurança. Caso o usuário tenha direito de alterar a documentação, ela pode ser alterada
direto no componente.

### Atributos

- **`key`:** Atributo **obrigatório**  que deve ser uma string que irá conter a chave que a documentação terá. Esta chave é a identificação da documentação no segurança.
- **`can-edit`:** Atributo **obrigatório** que deve ser um booleano que irá dizer se o usuário pode editar ou não o texto.
- **`api-url`:** Atributo **obrigatório** que deve ser uma string que irá conter a url da api que ele irá buscar os dados. Caso esteja usando o gumgaRest/gumgaController, existe um método `getDocumentationURL` para isto.
- **`modal-title`:** Atributo **opcional** que deve ser uma string que irá conter o título do modal.
- **`confirm-button`:** Atributo **opcional** que deve ser uma string que irá conter o texto que irá no botão de confirmar.
- **`confirm-button-class`:** Atributo **opcional** que deve ser uma string que irá conter qual classe o botão de confirmar assumirá.
