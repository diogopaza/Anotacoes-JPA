# Anotacoes-JPA

<p>O JPA disponibiliza anotações para marcar em que momento(pre/post – antes/depois) o método será executado em relação a ações do entityManager no objeto.</p>

Anotações:<br/>

<strong>@PrePersist</strong>: executa método anotado antes da entidade ser persistida;<br/>
<strong>@PostPersist</strong>: executa método anotado após entidade ser persistida;<br/>
<strong>@PreRemove</strong>:executa método anotado antes da entidade ser removida;<br/>
<strong>@PostRemove</strong>: executa método anotado após entidade ser removida;<br/>
<strong>@PreUpdate</strong>: executa método anotado antes da entidade ser atualizada;<br/>
<strong>@PostUpdate</strong>:executa método anotado após entidade ser persistida;<br/>
<strong>@PostLoad</strong>: executa método anotado após entidade carregada(consultada);<br/>
