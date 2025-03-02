# reactsintaxe
REACT - Biblioteca Java Script

------------------------------------------------------------------------------------------
# 027 - Comentários

// Lógica - Tipo de Comentário-1

/**
 * Lógica - Tipo de Comentário-2
 * 
 * Multi-line
 *   
 */

const FirstComponent = () => {
    return (
        <div>
            {/* JSX - Tipo de Comentário */}
            <h1>Meu primeiro componente</h1>            
        </div>
    );     
};

export default FirstComponent;

------------------------------------------------------------------------------------------
# 027 - Template Expression
const TemplateExpression  = () => {

    const name = "Ulisses Moraes";
    const data = {
        age: 50,
        profession: "Analista de Sistemas",
        experience: 28      
    }
    
    return (
        <div>
            <h1>Olá, meu nome é {name}, tenho {data.age} anos de idade, 
                trabalho como {data.profession} e tenho {data.experience} de experiência.
            </h1>
            <p>{console.log("JSX React - Bora pra cima Carioca!!")}</p>
        </div>
    )

}

export default TemplateExpression;

------------------------------------------------------------------------------------------

