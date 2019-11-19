# ¿Qué comando utilizaste en el paso 11? ¿Por qué?

```
git reset --hard HEAD~1
```

Porque reset permite deshacer un commit sin dejar working copy y HEAD~1 apunta al primer 'padre' del commit actual es decir al que queremos volver.

# ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

```
git reflog
git reset --hard HEAD@{1}
```

Reflog para ver un registro de los antiguos heads y Reset a HEAD@{1} para ir al commit en el que estabamos antes del reset anterior.

# El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No, porque está haciendo un merge con un branch que es padre del branch styled.

# El merge del paso 19, ¿Causó algún conflicto? ¿Por qué? 

Si, ya que hay cambios guardados de diferentes ramas en el mismo archivo.

# El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué?

No, porque los cambios desde master a styled ya existían en los commit del branch styled.

# ¿Qué comando o comandos utilizaste en el paso 25?

```
git log --graph
```

# El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Si, podría ser fast forward porque no hay cambios nuevos en la rama master desde que generamos la rama 'title'.

# ¿Qué comando o comandos utilizaste en el paso 27?
```
git reset --soft HEAD~1
```
# ¿Qué comando o comandos utilizaste en el paso 28?
```
git checkout git-nuestro.md 
```
# ¿Qué comando o comandos utilizaste en el paso 29?
```
git branch -D title 
```
# ¿Qué comando o comandos utilizaste en el paso 30?
```
git reflog
git reset --hard HEAD@{4} 
```
(El merge estaba en la posición 4)
# ¿Qué comando o comandos usaste en el paso 32?
```
git reset --hard 50a2f2
```
# ¿Qué comando o comandos usaste en el punto 33?
```
git reset --hard e3bada
```
