# scala learnings
## traits vs abstract
1) traits do not have constructor parameters
2) mulitple traits can be inherited by the same class
3) triats ==>> should describe the behaviour || abstract class ==>> should indicate the things

## scala type hierarchy
scala.Any => scala.AnyRef[(java.lang.object) (String, List, Set)] => scala.Null <br>
scala.Any => scala.AnyVal[(Int, Unit, Boolean, Float), (we rarely extends this for memory optimizations etc)] => scala.Nothing
