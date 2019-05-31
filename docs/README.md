![logo](images/Title.png)

<P><img src="images/spacer-900.png"></P>

<H3>Table of Contents</H3>
<UL>
<LI><a href="#MISCELLANY">The JDK research</a><br>
<LI><a href="#STUDY_01">Research project about Java Platform Module System</a><br>
<LI><a href="#STUDY_02">Research project about Bean Validation, CDI, and RESTful Web Services</a><br>
<LI><a href="#STUDY_03">Research project about EJB, JPA, JMS, and JTA</a><br>
<LI><a href="#STUDY_04">Research project about Web Services</a><br>
<LI><a href="#STUDY_05">Spring Boot research project about Reactive RESTful Web Services, Spring HATEOAS, and Spring MVC Web Application</a><br>
<LI><a href="#STUDY_06">Spring Boot research project about SOAP Web Services</a><br>
<LI><a href="#STUDY_07">Spring Boot research project about RESTful Web Services</a><br>
<LI><a href="#STUDY_08">Spring Boot research project about Spring Cloud Netflix Microservices</a><br>
<LI><a href="#STUDY_09">Research project about security</a><br>
<LI><a href="#STUDY_10">Research project about mathematics</a><br>
<LI><a href="#LIBRARIES">Research project about libraries</a><br>
<LI><a href="#KP_SEAM01">KP_Seam01 application</a>
<LI><a href="#KP_EJB01">KP_EJB01 application</a>
<LI><a href="#KP_HIBERNATE02">KP_Hibernate02 application</a>
<LI><a href="#KP_HIBERNATE01">KP_Hibernate01 application</a>
<LI><a href="#KP_SPRING01">KP_Spring01 application</a>
</UL>

<P><img src="images/spacer-900.png"></P>

<H3 id="MISCELLANY">https://github.com/ee-eng-cs/Miscellany</BR>
The JDK research</H3>

<P><TABLE><TR><TD><a href="https://docs.oracle.com/en/java/javase/12/docs/api/index.html">
Oracle JDK 12</a></TD></TR></TABLE><P>

<P><TABLE>
<CAPTION><a href="https://github.com/ee-eng-cs/Miscellany/tree/master/src/main/java/a/latest/java/subjects/">
	Streams</a> &amp;
	<a href="https://github.com/ee-eng-cs/Miscellany/blob/master/src/main/java/kp/methods/">
	Methods</a></CAPTION>
<TR>
	<TD>Operator</TD>
	<TD>Consumer</TD>
	<TD>Supplier</TD>
	<TD>Predicate</TD>
	<TD>Parallelism</TD>
	<TD>Optionals</TD>
</TR><TR>
	<TD COLSPAN="2">Lambda Expressions</TD>
	<TD COLSPAN="2">Method References</TD>
	<TD COLSPAN="2">Functional Interface</TD>
</TR><TR>
	<TD COLSPAN="6"></TD>
</TR><TR>
	<TD>Sorting</TD>
	<TD><a href="https://github.com/ee-eng-cs/Miscellany/blob/master/src/main/java/a/latest/java/subjects/StreamCollecting.java">
		Collecting</a></TD>
	<TD>Filtering</TD>
	<TD>Grouping</TD>
	<TD>Partitioning</TD>
	<TD><a href="https://github.com/ee-eng-cs/Miscellany/blob/master/src/main/java/a/latest/java/subjects/StreamFragmentation.java">
		Fragmentation</a></TD>
</TR>
</TABLE></P>

<P><a href="https://github.com/ee-eng-cs/Miscellany/blob/master/src/main/java/a/latest/java/subjects/Var.java">
Local Variable Type Inference</a></P>

<P><TABLE>
<CAPTION><a href="https://github.com/ee-eng-cs/Miscellany/blob/master/src/main/java/a/latest/java/subjects/DateAndTimeChanging.java">
	Date &amp; Time</a></CAPTION>
<TR>
	<TD>Converting</TD>
	<TD>Formatting</TD>
	<TD><a href="https://github.com/ee-eng-cs/Miscellany/blob/master/src/main/java/a/latest/java/subjects/DateAndTimeAggregation.java">
		Aggregation</a></TD>
	<TD>Temporal Query</TD>
</TR>
</TABLE></P>

<P><TABLE>
<CAPTION><a href="https://github.com/ee-eng-cs/Miscellany/blob/master/src/main/java/kp/files/">
	Files</a></CAPTION>
<TR>
	<TD>File Streams &amp; Channels</TD>
	<TD>ZIP Files</TD>
	<TD>XML Files</TD>
	<TD>File Visitor</TD>
</TR>
</TABLE></P>

<P><TABLE>
<CAPTION><a href="https://github.com/ee-eng-cs/Miscellany/blob/master/src/main/java/kp/processes/">
	Processes</a></CAPTION>
<TR>
	<TD>Process Builder</TD>
	<TD>Process Handle</TD>
</TR>
</TABLE></P>

<P><TABLE>
<CAPTION><a href="https://github.com/ee-eng-cs/Miscellany/blob/master/src/main/java/kp/reactive/streams/">
	Reactive Streams</a></CAPTION>
<TR>
	<TD>Flow-Controlled Publishers &amp; Subscribers</TD>
	<TD>Asynchronous Streams of Data with Non-Blocking Back Pressure</TD>
</TR>
</TABLE></P>

<P><TABLE>
<CAPTION><a href="https://github.com/ee-eng-cs/Miscellany/blob/master/src/main/java/kp/regex/">
	Regular Expressions</a></CAPTION>
<TR>
	<TD>Matchers &amp; Patterns</TD>
	<TD>Split Tokenizing</TD>
	<TD>Scanner Tokenizing</TD>
</TR>
</TABLE></P>

<P><TABLE>
<CAPTION><a href="https://github.com/ee-eng-cs/Miscellany/blob/master/src/main/java/kp/web/">
	Web Servers &amp; Sockets</a></CAPTION>
<TR>
	<TD>Insecure &amp; Secure Sockets</TD>
	<TD>Synchronous &amp; Asynchronous HTTP Clients</TD>
	<TD>Embedded HTTP Server</TD>
</TR>
</TABLE></P>

<P><TABLE>
<CAPTION><a href="https://github.com/ee-eng-cs/Miscellany/blob/master/0_batch/03%20Batch%20Menu.bat">
	JVM</a></CAPTION>
<TR>
	<TD>Unified JVM Logging</TD>
	<TD>Class File Disassembler</TD>
</TR>
</TABLE></P>

<P><img src="images/spacer-900.png"></P>

<H3 id="STUDY_01">https://github.com/ee-eng-cs/Study01</BR>
Research project about Java Platform Module System</H3>

The researched problems:<br>

1. Declare Java module. Solution: [Java module declarations](https://github.com/ee-eng-cs/Study01#declarations).<br>
2. Locate and load service providers using <I>ServiceLoader</I>. Solution: [<I>KpService</I> implementations](https://github.com/ee-eng-cs/Study01#implementations).<br>
3. Load only selected service providers. Solution: [filter <I>Provider</I> stream in <I>KpServiceClient</I>](https://github.com/ee-eng-cs/Study01/tree/master/service-client/src/main/java/kp/client/KpServiceClient.java)<br>

<P><img src="images/spacer-900.png"></P>

<H3 id="STUDY_02">https://github.com/ee-eng-cs/Study02</BR>
Research project about Bean Validation, CDI, and RESTful Web Services</H3>

The researched problems:<br>

:one: Concerning Bean Validation<br>
1.1. Use property-level constraint and field-level constraint. Solution: [Validation Example 'Validate Item'](https://github.com/ee-eng-cs/Study02#valid_item).<br>
1.2. Inherit the constraint from the interface. Solution: [Validation Example 'Validate Item'](https://github.com/ee-eng-cs/Study02#valid_item).<br>
1.3. Use constraint @Pattern. Solution: [Validation Example 'Validate Item'](https://github.com/ee-eng-cs/Study02#valid_item).<br>
1.4. Use validation cascading on the list of objects with constraints. Solution: [Validation Example 'Validate Box Of Items'](https://github.com/ee-eng-cs/Study02#valid_box).<br>
1.5. Use constraints @NotNull, @DecimalMin, @DecimalMax. Solution: [Validation Example 'Validate Box Of Items'](https://github.com/ee-eng-cs/Study02#valid_box).<br>
1.6. Use constraints on the method parameter and return value. Solution: [Validation Example 'Validate Method'](https://github.com/ee-eng-cs/Study02#valid_method).<br>

:two: Concerning CDI<br>
2.1. Implement the alternative bean. Solution: [CDI Example 'Alternative &amp; Qualified Beans'](https://github.com/ee-eng-cs/Study02#c_d_i_alternative).<br>
2.2. Implement the bean with qualifier. Solution: [CDI Example 'Alternative &amp; Qualified Beans'](https://github.com/ee-eng-cs/Study02#c_d_i_alternative).<br>
2.3. Use the qualifier with parameters. Solution: [CDI Example 'Alternative &amp; Qualified Beans'](https://github.com/ee-eng-cs/Study02#c_d_i_alternative).<br>
2.4. Implement the decorated bean. Solution: [CDI Example 'Decorated Beans'](https://github.com/ee-eng-cs/Study02#c_d_i_decorated).<br>
2.5. Use the interceptor for the elapsed time measuring. Assess the feasibility of that idea for very short times.<br>
   <img src="images/spacer-32.png">Solution: [CDI Example 'Intercepted Beans'](https://github.com/ee-eng-cs/Study02#c_d_i_intercepted).<br>
2.6. Implement the observers of events. Check the CDI advantage: no type erasure for event type.<br>
   <img src="images/spacer-32.png">Solution: [CDI Example 'Events'](https://github.com/ee-eng-cs/Study02#c_d_i_events).<br>

:three: Concerning RESTful Web Services<br>
3.1. Use path and query parameters in HTTP requests. Solution: [RESTful Example 'Content GET'](https://github.com/ee-eng-cs/Study02#r_e_s_t_f_u_l_content).<br>
3.2. Implement resource method for CREATE, READ, UPDATE, and DELETE functions.<br>
   <img src="images/spacer-32.png">Solution: [RESTful Example 'Boxes CRUD (Internal Client)'](https://github.com/ee-eng-cs/Study02#r_e_s_t_f_u_l_boxes_internal).<br>
3.3. Run that CRUD implementation with the external client. Solution: [RESTful Example 'Boxes CRUD (External Client)'](https://github.com/ee-eng-cs/Study02#r_e_s_t_f_u_l_boxes_external).<br>

<P><img src="images/spacer-900.png"></P>

<H3 id="STUDY_03">https://github.com/ee-eng-cs/Study03</BR>
Research project about EJB, JPA, JMS, and JTA</H3>

The researched problems:<br>

:one: Concerning EJB<br>
1.1 Use the enterprise session beans in concurrent tasks. Solution: [EJB Example 'Tasks'](https://github.com/ee-eng-cs/Study03/tree/master/docs#e_j_b_tasks).<br>
1.2 Show the bean state preservation in stateless and in stateful session beans. Solution: [EJB Example 'Tasks'](https://github.com/ee-eng-cs/Study03/tree/master/docs#e_j_b_tasks).<br>
1.3 Invoke no-interface view bean, local bean, and remote bean. Solution: [EJB Example 'Checks'](https://github.com/ee-eng-cs/Study03/tree/master/docs#e_j_b_checks).<br>
1.4 Intercept EJB method invocation for capturing the elapsed time. Solution: [EJB Example 'Interceptor'](https://github.com/ee-eng-cs/Study03/tree/master/docs#e_j_b_interceptor).<br>

:two: Concerning JPA<br>
2.1 Implement CRUD actions with named queries or criteria queries (without or with metamodel).<br>
   <img src="images/spacer-32.png">Solution: examples in [Research JPA](https://github.com/ee-eng-cs/Study03/tree/master/docs#j_p_a).<br>
2.2 Show <I>one-to-one</I>, <I>one-to-many</I>, <I>many-to-one</I>, and <I>many-to-many</I> relationships. Solution: [JPA Example 'Boxes'](https://github.com/ee-eng-cs/Study03/tree/master/docs#j_p_a_boxes).<br>
2.3 Show <I>previous-next</I> and <I>parent-child</I> self-referential relationships. Solution: [JPA Example 'Units'](https://github.com/ee-eng-cs/Study03/tree/master/docs#j_p_a_units).<br>
2.4 Show hierarchical multilevel relationships. Solution: [JPA Example 'Levels'](https://github.com/ee-eng-cs/Study03/tree/master/docs#j_p_a_levels).<br>
2.5 Use entity fields with enumerations or typical date/time representations. Solution: examples in [Research JPA](https://github.com/ee-eng-cs/Study03/tree/master/docs#j_p_a).<br>

:three: Concerning JMS<br>
3.1 Implement synchronous queue and topic. Solution: [JMS Example 'Synchronous Queue &amp; Topic'](https://github.com/ee-eng-cs/Study03/tree/master/docs#j_m_s_sync).<br>
3.2 Implement asynchronous queue and topic. Use message driven beans.<br>
   <img src="images/spacer-32.png">Solution: [JMS Example 'Asynchronous Queue &amp; Topic'](https://github.com/ee-eng-cs/Study03/tree/master/docs#j_m_s_async).<br>
3.3 Implement reply queue for message confirmation. Solution: examples in [Research JMS](https://github.com/ee-eng-cs/Study03/tree/master/docs#j_m_s).<br>

:four: Concerning JTA CMT. Solution: [Research CMT](https://github.com/ee-eng-cs/Study03/tree/master/docs#trans_c_m_t).<br>
4.1 Implement CRUD actions with the container-managed transactions.<br>
4.2 Use together JMS asynchronous queues and database in the container-managed transaction.<br>
4.3 Having the JMS queue and the database together in one transaction,<br>
   <img src="images/spacer-32.png">show that the rollback of this transaction causes rolled back message redelivery.<br>
4.4 Having the JMS queue consumer and queue sender together in one transaction,<br>
   <img src="images/spacer-32.png">show that the rollback of that transaction cancels the message sending.<br>
4.5 Process the auditing in a new transaction, so that audit information is not lost when the main transaction is rolled back.<br>
4.6 For JMS queues define qualifiers with enumeration.<br>

:five: Concerning JTA BMT. Solution: [Research BMT](https://github.com/ee-eng-cs/Study03/tree/master/docs#trans_b_m_t).<br>
5.1 Implement CRUD actions with the bean-managed transactions.<br>
5.2 Investigate the special case: <I>in a stateful session bean with a JTA transaction<br>
   <img src="images/spacer-32.png">the association between the bean instance and the transaction is retained across multiple client calls</I>.<br>

<P><img src="images/spacer-900.png"></P>

<H3 id="STUDY_04">https://github.com/ee-eng-cs/Study04</BR>
Research project about Web Services</H3>

The researched problems:<br>

:one: Concerning JAX-WS. Solution: [Research Web Services](https://github.com/ee-eng-cs/Study04/tree/master/docs#w_s).<br>
1.1 Create web services using annotations and tools "wsgen", "wsimport".<br>
1.2 Implement clients on different environments:<br>
   <img src="images/spacer-32.png">- the web client<br>
   <img src="images/spacer-32.png">- the JBoss application client<br>
   <img src="images/spacer-32.png">- the Java SE client<br>
1.3 Implement clients with different ways of calling:<br>
   <img src="images/spacer-32.png">- The synchronous invocation<br>
   <img src="images/spacer-32.png">- The asynchronous invocation that uses the polling mechanism<br>
   <img src="images/spacer-32.png">- The asynchronous invocation that uses the callback mechanism<br>
 
:two: Concerning JAX-RS.<br>
2.1 Implement the RESTful web service and call it from web application. Solution: [Research RESTful Web Services](https://github.com/ee-eng-cs/Study04/tree/master/docs#r_s).<br>

<P><img src="images/spacer-900.png"></P>

<H3 id="STUDY_05">https://github.com/ee-eng-cs/Study05</BR>
Spring Boot research project about Reactive RESTful Web Services,</BR>
Spring HATEOAS, and Spring MVC Web Application</H3>

The researched problems:<br>

:one: Concerning Reactive RESTful Web Services. Solution: [Reactive Web Services](https://github.com/ee-eng-cs/Study05#reactive).<br>
1.1. Implement reactive web services with Spring Boot and Spring WebFlux reactive web framework.<br>
1.2. Perform HTTP requests:<br>
   <img src="images/spacer-32.png">- with web browser<br>
   <img src="images/spacer-32.png">- with non-blocking, reactive client<br>
1.3. Add Spring Boot tests with WebTestClient.<br>

:two: Concerning Spring HATEOAS. Solution: [Hypermedia-based RESTful Web Services](https://github.com/ee-eng-cs/Study05#hypermedia).<br>
2.1. Create an application that accesses relational JPA data through a hypermedia-based RESTful front end.<br>
2.2. In resource assemblers define link driven representations for REST webservices.<br>
2.3. Show ALPS (Application-Level Profile Semantic) profiles for departments and employees.<br>
2.4. Enable all Spring Boot Actuator endpoints.<br>
2.5. Use embedded, in-memory database.<br>
2.6. Use CRUD operations implemented in Spring JpaRepository.<br>
2.7. Implement additional repository methods by extending the Spring JpaRepository.<br>
2.8. Declare the finder query with an annotation on a repository method.<br>
2.9. Add Spring Boot tests with TestRestTemplate and MockMvc.<br>
2.10. Add JPA repository tests.<br>

:three: Concerning Spring MVC Web Application. Solution: [Web Application](https://github.com/ee-eng-cs/Study05#web).<br>
3.1. Implement web application with Spring Boot, Spring MVC, and Thymeleaf.<br>
3.2. Implement CRUD actions.<br>
3.3. Annotate the beans with the Bean Validation API provided constraints.<br>
3.4. Add Spring Boot tests with TestRestTemplate and MockMvc.<br>


<P><img src="images/spacer-900.png"></P>

<H3 id="STUDY_06">https://github.com/ee-eng-cs/Study06</BR>
Spring Boot research project about SOAP Web Services</H3>

The researched problems:<br>
1. With Spring-WS implement on server the SOAP Web Services. Generate it from XML schema file.<br>
2. With Spring-WS implement the SOAP Web Services client. Generate it from WSDL file.<br>
3. Add Spring Boot tests with WebServiceTemplate, MockWebServiceServer, and MockWebServiceClient.<br>

<P>Solution: <a href="https://github.com/ee-eng-cs/Study06">SOAP Web Services</a>.</P>

<P><img src="images/spacer-900.png"></P>

<H3 id="STUDY_07">https://github.com/ee-eng-cs/Study07</BR>
Spring Boot research project about RESTful Web Services</H3>

The researched problems:<br>
1. Implement RESTful web services with Spring Boot and Spring MVC.<br>
2. Consume REST Web Services:<br>
<img src="images/spacer-32.png">- with web browser client<br>
<img src="images/spacer-32.png">- with Spring command line runner client<br>
<img src="images/spacer-32.png">- with 'AngularJS' client<br>
<img src="images/spacer-32.png">- with 'jQuery' client<br>
3. Add Spring Boot tests with TestRestTemplate and MockMvc.<br>

<P>Solution: <a href="https://github.com/ee-eng-cs/Study07">RESTful Web Services</a>.</P>

<P><img src="images/spacer-900.png"></P>

<H3 id="STUDY_08">https://github.com/ee-eng-cs/Study08</BR>
Spring Boot research project about Spring Cloud Netflix Microservices</H3>

The researched problems:<br>
1. Implement microservices with Spring Boot and Eureka server.<br>
2. Implement fallback method with Hystrix circuit breaker.<br>
3. Enable Spring Boot Actuator endpoints.<br>

<P>Solution: <a href="https://github.com/ee-eng-cs/Study08">Microservices</a>.</P>

<P><img src="images/spacer-900.png"></P>

<H3 id="STUDY_09">https://github.com/ee-eng-cs/Study09</BR>
Research project about security</H3>

<P><TABLE>
<CAPTION>Subjects (with Java source code linked)</CAPTION>
<TR>
	<TD><a href="https://github.com/ee-eng-cs/Study09/blob/master/src/main/java/kp/security/ecc/EllipticCurveCryptography.java">
		Elliptic Curve Cryptography</a></TD>
	<TD><a href="https://github.com/ee-eng-cs/Study09/blob/master/src/main/java/kp/security/CiphersEncryptionAndDecryption.java">
		Ciphers Encryption and Decryption</a></TD>
	<TD><a href="https://github.com/ee-eng-cs/Study09/blob/master/src/main/java/kp/security/SignaturesSigning.java">
		Signing the Signatures</a></TD>
</TR><TR>
	<TD><a href="https://github.com/ee-eng-cs/Study09/blob/master/src/main/java/kp/security/KeysAndDigestsExchanging.java">
		Exchanging Keys and Digests</a></TD>
	<TD><a href="https://github.com/ee-eng-cs/Study09/blob/master/src/main/java/kp/security/MacsComputing.java">
		Message Authentication Codes</a></TD>
	<TD><a href="https://github.com/ee-eng-cs/Study09/blob/master/src/main/java/kp/security/ChecksumsComputing.java">
		Checksums Computing</a></TD>
</TR><TR>
	<TD><a href="https://github.com/ee-eng-cs/Study09/blob/master/src/main/java/kp/security/DigestsComputing.java">
		Message Digests Computing</a></TD>
	<TD><a href="https://github.com/ee-eng-cs/Study09/blob/master/src/main/java/kp/security/PasswordValidation.java">
		Password Validation</a></TD>
	<TD><a href="https://github.com/ee-eng-cs/Study09/blob/master/src/main/java/kp/security/SecureClass.java">
		Hidden Constructor</a></TD>
</TR>
</TABLE></P>

<P><img src="images/spacer-900.png"></P>

<H3 id="STUDY_10">https://github.com/ee-eng-cs/Study10</BR>
Research project about mathematics</H3>
<P><TABLE>
<CAPTION>Subjects (with Java source code linked)</CAPTION>
<TR>
	<TD><a href="https://github.com/ee-eng-cs/Study10/blob/master/src/main/java/kp/math/CachedNumbers.java">
		Cached Numbers</a></TD>
	<TD><a href="https://github.com/ee-eng-cs/Study10/blob/master/src/main/java/kp/math/NumberInCompactForm.java">
		Number in Compact Form</a></TD>
	<TD><a href="https://github.com/ee-eng-cs/Study10/blob/master/src/main/java/kp/math/CubesAndRoots.java">
		Cubes &amp; Roots</a></TD>
	<TD><a href="https://github.com/ee-eng-cs/Study10/blob/master/src/main/java/kp/math/EvenAndOddNumbers.java">
		Evens &amp; Odds</a></TD>
</TR><TR>
	<TD COLSPAN="2"><a href="https://github.com/ee-eng-cs/Study10/blob/master/src/main/java/kp/math/Means.java">
		Means</a> (Arithmetic, Harmonic, Geometric, Quadratic)</TD>
	<TD COLSPAN="2">Big Numbers:
		<a href="https://github.com/ee-eng-cs/Study10/blob/master/src/main/java/kp/math/VeryBigIntegerRaised.java">Raised</a>,
		<a href="https://github.com/ee-eng-cs/Study10/blob/master/src/main/java/kp/math/VeryBigIntegerRandomlyGenerated.java">Generated</a>,
		<a href="https://github.com/ee-eng-cs/Study10/blob/master/src/main/java/kp/math/BigDecimalsFromStringRepresentation.java">Multiplied</a></TD>
</TR><TR>
	<TD><a href="https://github.com/ee-eng-cs/Study10/blob/master/src/main/java/kp/math/GoldenRatio.java">
		Golden Ratio</a></TD>
	<TD><a href="https://github.com/ee-eng-cs/Study10/blob/master/src/main/java/kp/math/FibonacciNumbers.java">
		Fibonacci Numbers</a></TD>
	<TD><a href="https://github.com/ee-eng-cs/Study10/blob/master/src/main/java/kp/math/Logic.java">
		Logic Aggregated</a></TD>
	<TD></TD>
</TR><TR>
	<TD COLSPAN="4"></TD>
</TR><TR>
	<TD><a href="https://github.com/ee-eng-cs/Study10/blob/master/src/main/java/kp/math/statistics/SummaryStatistics.java">
		Summary Statistics</a></TD>
	<TD><a href="https://github.com/ee-eng-cs/Study10/blob/master/src/main/java/kp/math/statistics/bayes/">
		Bayes' Theorem</a></TD>
	<TD></TD>
	<TD></TD>
</TR>
</TABLE></P>

<P><img src="images/spacer-900.png"></P>

<H3 id="LIBRARIES">https://github.com/ee-eng-cs/LibrariesAssay</BR>
Research project about libraries</H3>
<P><TABLE>
<CAPTION>Subjects (with Java source code linked)</CAPTION>
<TR>
	<TD><a href="https://github.com/ee-eng-cs/LibrariesAssay/blob/master/src/main/java/kp/ApacheCommonsCollections.java">
		Apache Commons Collections</a></TD>
	<TD><a href="https://github.com/ee-eng-cs/LibrariesAssay/blob/master/src/main/java/kp/ConcurrentTrees.java">
		Concurrent Radix &amp; Suffix Trees</a></TD>
	<TD><a href="https://github.com/ee-eng-cs/LibrariesAssay/blob/master/src/main/java/kp/EclipseCollections.java">
		Eclipse Collections</a></TD>
</TR>
</TABLE></P>

<P><img src="images/spacer-900.png"></P>

<H3>Applications</H3>

<p id="KP_SEAM01">:one: <a href="https://github.com/ee-eng-cs/KP_Seam01">https://github.com/ee-eng-cs/KP_Seam01</a><br>
	<img src="images/spacer-32.png">CDI and JSF web application <i>(JBoss EAP)</i></p>
	
<p id="KP_EJB01">:two: <a href="https://github.com/ee-eng-cs/KP_EJB01">https://github.com/ee-eng-cs/KP_EJB01</a><br>
	<img src="images/spacer-32.png">EJB 3 and Struts web application <i>(JBoss EAP)</i></p>
	
<p id="KP_HIBERNATE02">:three: <a href="https://github.com/ee-eng-cs/KP_Hibernate02">https://github.com/ee-eng-cs/KP_Hibernate02</a><br>
	<img src="images/spacer-32.png">Hibernate and JSF web application <i>(Tomcat)</i></p>
	
<p id="KP_HIBERNATE01">:four: <a href="https://github.com/ee-eng-cs/KP_Hibernate01">https://github.com/ee-eng-cs/KP_Hibernate01</a><br>
	<img src="images/spacer-32.png">Hibernate and SWT application <i>(rich client)</i></p>
	
<p id="KP_SPRING01">:five: <a href="https://github.com/ee-eng-cs/KP_Spring01">https://github.com/ee-eng-cs/KP_Spring01</a><br>
	<img src="images/spacer-32.png">Spring Framework web application <i>(Tomcat)</i></p>

<P><img src="images/spacer-900.png"></P>