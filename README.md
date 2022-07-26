# Anotacoes-JPA

<p>O JPA disponibiliza anotações para marcar em que momento(pre/post – antes/depois) o método será executado em relação a ações do entityManager no objeto.</p>

Anotações:<br/>

@PrePersist: executa método anotado antes da entidade ser persistida;<br/>
@PostPersist: executa método anotado após entidade ser persistida;<br/>
@PreRemove:executa método anotado antes da entidade ser removida;<br/>
@PostRemove: executa método anotado após entidade ser removida;<br/>
@PreUpdate: executa método anotado antes da entidade ser atualizada;<br/>
@PostUpdate:executa método anotado após entidade ser persistida;<br/>
@PostLoad: executa método anotado após entidade carregada(consultada);<br/>
