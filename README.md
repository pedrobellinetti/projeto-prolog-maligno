Objetivos:

1. curso(cc,nc)

- cc = curso com código
- nc = nome do curso

Objetivo: Indicar que existe um curso com código(cc) e nome do curso(nc)

2. materia(cm, nm, am)

- cm = código da matéria
- nm = nome da matéria
- am = quantidade de aulas por semana

Objetivo: Indicar que existe uma matéria com código (cm), nome (nm)
e quantidade de aulas por semana (am)

3. curriculo(cc, [ cm1, cm2,...,cmn ])

- cc = curso com código
- cm1 = código da matéria

Objetivo = Indicar que as matérias(cm1) com código fazem parte do curso com código (cc)

4. aluno(ra,na)

- ra = ra do aluno
- cc = curso com código

Objetivo: Indicar que existe um aluno com RA: ra e nome: na

5. cursa(ra, cc)

- ra = ra do aluno
- cc = curso com código

Objetivo: Indicar que o aluno com RA: ra cursa o curso com código: cc

6. historico(ra, [ i1, i2, ..., in ])
   ra = ra do aluno
   i1 = functor com a forma item(cm, sm, an, nt, fq), sendo que:
   cm = código de uma matéria
   sm = semestre no qual o item foi cursado
   an = ano no qual o item foi cursado
   nt = nota que o aluno obteve quando cursou aquele curso
   fq = frequência que o aluno obteve quando cursou aquele item
