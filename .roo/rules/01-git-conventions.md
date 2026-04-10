# Convenciones de Git para Modos Roo Code

Para asegurar la trazabilidad y el orden en el patrón de orquestación, todos los modos que modifiquen código DEBEN seguir estas reglas:

1. **Commits Atómicos**: Un commit por tarea lógica o hito del plan.
2. **Mensajes Descriptivos**: 
   - Estructura: `tipo(scope): descripción`
   - Tipos: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`.
3. **Persistencia**: Siempre haz `git add .` seguido de `git commit -m "..."` después de verificar que los cambios funcionan.
4. **Resumen en Subtarea**: Al finalizar una subtarea con `attempt_completion`, incluye el hash del último commit realizado.
