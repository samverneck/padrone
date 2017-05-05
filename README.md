# padrone

## Estrutura de arquivos

```
src
..index.html
..main.ts           * ponto de entrada da app
..app/
....app.component.controller.ts         /* controller da app
....app.component.scss                   
....app.component.html                  
....app.component.ts                    
....app.module.ts                       /* módulo principal da app  (registra rotas, componentes, serviços, etc)
....vendors.ts                          
....shared/     * funconalidades compartilhadas pelas features
....featureA/
......shared/       * funcionalidades compartilhadas dentro da feature
......featureA.component.controller.ts 
......featureA.component.scss 
......featureA.component.html
......featureA.component.ts
......featureA.module.ts  
....featureB/
......shared/      
......featureB.component.controller.ts 
......featureB.component.scss 
......featureB.component.html
......featureB.component.ts
......featureB.module.ts 
....featureC/
......shared/      
......featureC.module.ts     * modulo da feature (registra rotas, componentes, serviços, etc)
......subFeatureC1/
........subFeatureC1.component.controller.ts 
........subFeatureC1.component.scss 
........subFeatureC1.component.html
........subFeatureC1.component.ts
......subFeatureC2/
........subFeatureC2.component.controller.ts 
........subFeatureC2.component.scss 
........subFeatureC2.component.html
........subFeatureC2.component.ts
.
.
.
```
