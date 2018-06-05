![UML Diagram](https://g.gravizo.com/source/svg/class_uml?https%3A%2F%2Fraw.githubusercontent.com%2FOpenWaterAnalytics%2Fnext-net%2Fmaster%2Fclass_uml.md)
<details> 
<summary></summary>
class_uml
import java.util.List;
/**************************
 *@opt inferrel
 *@opt collpackages java.util.*
 *@opt inferdep
 *@hidden
 */
class UMLOptions {}
/**************************
*@opt attributes
*/
class Element {
    public string name;
}
/**************************
*@opt attributes
*/
class Node extends Element {
    public Coordinate location;
    public double elevation;
}
/**************************
*@opt attributes
*/
class Link extends Element {
    public Node from;
    public Node to;
}
/**************************
*@opt attributes
*/
class Pipe extends Link {
    public double length;
    public double diameter;
    public double roughness;
}
/**************************
*@opt attributes
*/
class Valve extends Link {
    public double setting;
}
/**************************
*@opt attributes
*/
class Pump extends Link {
    public double speed;
}
/**************************
*@opt attributes
*/
class Junction extends Node {
    public double demand;
}
/**************************
*@opt attributes
*/
class Tank extends Node {
    public double level;
}
/**************************
*@opt attributes
*/
class Reservoir extends Node {
    public double head;
}
/**************************
*@opt attributes
*@opt shape activeclass
*@opt inferreltype composed
*/
class Network {
 List<Node> nodes;
 List<Link> links;
}
)
