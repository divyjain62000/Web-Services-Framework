List of ServiceException 
-------------------------------------------------------------------------------------------------------------------------------------------------------------

1) ServicePackagePrefixException:  #

	No such package exists, which contains the value mentioned against SERVICE_PACKAGE_PREFIX in web.xml as a prefix.

-------------------------------------------------------------------------------------------------------------------------------------------------------------

2) ServicePackagePrefixNotFoundException:  #

	This is raise when  SERVICE_PACKAGE_PREFIX in param-name or value against it in param-value tag in web.xml is 
	not provided

-------------------------------------------------------------------------------------------------------------------------------------------------------------

3) RequestTypeConflictException:#
               You could not use both @GET and @Post annotations at a time on a single method or class.

-------------------------------------------------------------------------------------------------------------------------------------------------------------

4) LeaningOnPathException:#
	You did not implement the @Path annotation with one of the following annotations @GET, @ POST, @Forward ,
	@InjectSessionScope  ,@InjectRequestScope  ,@InjectApplicationScope  ,@InjectApplicationDirectoryScope  
	,@SecuredAccess

-------------------------------------------------------------------------------------------------------------------------------------------------------------

5) LeaningOnRequestTypeException:#
	You did not implement the @GET or @POST annotation with one of the following annotations @Forward ,@SecuredAccess

-------------------------------------------------------------------------------------------------------------------------------------------------------------

6) OnStartupException:#
	You cannot implement @OnStartup annotation along with other annotations present in the WebServicesFramework

-------------------------------------------------------------------------------------------------------------------------------------------------------------

7) IllegalInjectRequestParameterException:#
	You cannot apply @InjectRequestParameter annotation with data types other than primitive and java.lang.String

-------------------------------------------------------------------------------------------------------------------------------------------------------------

8) ExcessParameterTypeException:#
	 You cannot use more than one complex data type {except : java.lang.String,ApplicationScope,RequestScope,SessionScope
	 ,ApplicationDirectory} in single function over which @Path annotation is applied

-------------------------------------------------------------------------------------------------------------------------------------------------------------

9) ClassInstantiationException: #
	The instantiation can fail for a variety of reasons including but not limited to:
		(i) the class object represents an abstract class, an interface, an array class, a primitive type, or void
		(ii) the class has no nullary constructor

-------------------------------------------------------------------------------------------------------------------------------------------------------------

10) InvalidURLRequestException:#
	This exception occurs when you request some URL and it is not found

-------------------------------------------------------------------------------------------------------------------------------------------------------------

11) IllegalMethodException:#
	This exception occurs when you try to access resources through a method that is not allowed on that resource

-------------------------------------------------------------------------------------------------------------------------------------------------------------

12) IllegalGaurdParameterException:#
	This exception occurs when your gaurd method has parameters other than {ApplicationScope, SessionScope, RequestScope, 
	ApplicationDirectory}

-------------------------------------------------------------------------------------------------------------------------------------------------------------

13) IllicitAccessException: #
	An IllicitAccessException is thrown when an application tries to reflectively create an instance (other than an array), 
	set or get a field, or invoke a method, but the currently executing method does not have access to the definition of 
	the specified class, field, method or constructor.

-------------------------------------------------------------------------------------------------------------------------------------------------------------

14) InvalidNumberOfParameterException:#
	Method to which request has been forwarded has either 0 parameter or more than 1 parameters

-------------------------------------------------------------------------------------------------------------------------------------------------------------

15) SetterNotFoundException:
	This exception occurs when you do not define a setter method for the property of the {ApplicationScope,SessionScope
	,RequestScope or ApplicationDirectory} class type or you do not create a setter for the property to which you apply 
	@AutoWired annotation.

-------------------------------------------------------------------------------------------------------------------------------------------------------------

16) GaurdNotFoundException:
	This exception occurs when you do not define a gaurd method.

-------------------------------------------------------------------------------------------------------------------------------------------------------------

17) BaseURLNotFoundException:
	This is raise when  BASE_URL in param-name or value against it in param-value tag in web.xml is not provided.
	