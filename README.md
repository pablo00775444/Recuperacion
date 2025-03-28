# Recuperacion_funcionalidad_puntaje_tetris
En esta recuperacion voy a realizar un pseudocodigo,diagrama de flujo y algoritmo para saber como funciona el puntaje de un juego en este caso,tetris este es un juego donde al completar o 
acomodar las figuras de cierta manera estas explotaran y se nos otorgara un puntaje 



PSEUDOCODIGO
[Algoritmo funcionalidad_puntuaje_tetris
	DEFINIR puntaje COMO ENTERO;
	DEFINIR filas_completadas COMO ENTERO;
	DEFINIR numero COMO ENTERO;
	filas_completadas = 0;
	puntaje= 0; 
	numero=0;
	ESCRIBIR "Bienvenido a tetris";
	filas_completadas = numero;
	SI filas_completadas > 0 ENTONCES
	puntaje = puntaje + filas_completadas * 100;	
FinSI
ESCRIBIR"Juego terminado puntaje final:",puntaje;
FinAlgoritmo
Uploading PSEUDOCODIGO.psc…]()

![Captura de pantalla 2025-03-28 094531](https://github.com/user-attachments/assets/c366ff89-5a59-491e-8080-f8353fc6386e)


DIAGRAMA DE FLUJO
[U<mxfile host="app.diagrams.net" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/134.0.0.0 Safari/537.36" version="26.1.3">
  <diagram name="Página-1" id="yz_0NU_y8Ucjf3_ebRbI">
    <mxGraphModel dx="1034" dy="1623" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="IrhKcL5lx_eICvQf7MEP-6" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" parent="1" source="IrhKcL5lx_eICvQf7MEP-1" target="IrhKcL5lx_eICvQf7MEP-4" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-1" value="INICIO" style="ellipse;whiteSpace=wrap;html=1;" parent="1" vertex="1">
          <mxGeometry x="330" y="-550" width="150" height="80" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-2" value="FIN" style="ellipse;whiteSpace=wrap;html=1;" parent="1" vertex="1">
          <mxGeometry x="345" y="1000" width="120" height="80" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-7" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" parent="1" source="IrhKcL5lx_eICvQf7MEP-4" target="IrhKcL5lx_eICvQf7MEP-5" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-4" value="&lt;font style=&quot;vertical-align: inherit;&quot;&gt;&lt;font style=&quot;vertical-align: inherit;&quot;&gt;&lt;font style=&quot;vertical-align: inherit;&quot;&gt;&lt;font style=&quot;vertical-align: inherit;&quot;&gt;DEFINIR puntaje COMO ENTERO&lt;/font&gt;&lt;/font&gt;&lt;/font&gt;&lt;/font&gt;" style="rounded=0;whiteSpace=wrap;html=1;" parent="1" vertex="1">
          <mxGeometry x="345" y="-430" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-10" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" parent="1" source="IrhKcL5lx_eICvQf7MEP-5" target="IrhKcL5lx_eICvQf7MEP-8" edge="1">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-5" value="&lt;font style=&quot;vertical-align: inherit;&quot;&gt;&lt;font style=&quot;vertical-align: inherit;&quot;&gt;DEFINIR filas_completadas COMO ENTERO&lt;/font&gt;&lt;/font&gt;" style="rounded=0;whiteSpace=wrap;html=1;" parent="1" vertex="1">
          <mxGeometry x="345" y="-330" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-8" value="&lt;font style=&quot;vertical-align: inherit;&quot;&gt;&lt;font style=&quot;vertical-align: inherit;&quot;&gt;DEFINIR numero COMO ENTERO&lt;/font&gt;&lt;/font&gt;" style="rounded=0;whiteSpace=wrap;html=1;" parent="1" vertex="1">
          <mxGeometry x="345" y="-240" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-14" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" parent="1" source="IrhKcL5lx_eICvQf7MEP-11" edge="1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="405" y="310" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-11" value="&lt;font style=&quot;vertical-align: inherit;&quot;&gt;&lt;font style=&quot;vertical-align: inherit;&quot;&gt;ESCRIBIR&quot;Bienvenido a tetris &quot;&lt;/font&gt;&lt;/font&gt;" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;fixedSize=1;" parent="1" vertex="1">
          <mxGeometry x="255" y="180" width="300" height="80" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-24" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" parent="1" target="IrhKcL5lx_eICvQf7MEP-15" edge="1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="405" y="370" as="sourcePoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-16" value="SI" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" parent="1" source="IrhKcL5lx_eICvQf7MEP-15" edge="1">
          <mxGeometry x="0.1053" y="-5" relative="1" as="geometry">
            <mxPoint x="600" y="540" as="targetPoint" />
            <Array as="points">
              <mxPoint x="600" y="455" />
            </Array>
            <mxPoint x="5" y="-5" as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-17" value="NO" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" parent="1" source="IrhKcL5lx_eICvQf7MEP-15" edge="1">
          <mxGeometry x="-0.0658" y="-5" relative="1" as="geometry">
            <mxPoint x="240" y="540" as="targetPoint" />
            <Array as="points">
              <mxPoint x="241" y="455" />
            </Array>
            <mxPoint x="5" y="-5" as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-15" value="&lt;font style=&quot;vertical-align: inherit;&quot;&gt;&lt;font style=&quot;vertical-align: inherit;&quot;&gt;filas_completadas es &amp;gt; 0&lt;/font&gt;&lt;/font&gt;" style="rhombus;whiteSpace=wrap;html=1;" parent="1" vertex="1">
          <mxGeometry x="315" y="400" width="180" height="110" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-18" value="ESCRIBIR &quot;No completo ninguna fila&quot;" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;fixedSize=1;" parent="1" vertex="1">
          <mxGeometry x="150" y="540" width="160" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IErN1is4IflzrCL0zltt-16" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=1;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" target="IErN1is4IflzrCL0zltt-11">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="530" y="950" as="targetPoint" />
            <mxPoint x="630" y="710" as="sourcePoint" />
            <Array as="points">
              <mxPoint x="600" y="710" />
              <mxPoint x="600" y="860" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-19" value="ESCRIBIR &quot;su puntaje es ,puntaje&quot;" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;fixedSize=1;" parent="1" vertex="1">
          <mxGeometry x="520" y="650" width="180" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-21" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" parent="1" source="IrhKcL5lx_eICvQf7MEP-20" target="IrhKcL5lx_eICvQf7MEP-19" edge="1">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="600" y="610" />
              <mxPoint x="600" y="610" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-20" value="puntaje = puntuaje + filas_completadas * 100" style="rounded=0;whiteSpace=wrap;html=1;" parent="1" vertex="1">
          <mxGeometry x="510" y="540" width="170" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IErN1is4IflzrCL0zltt-6" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="IErN1is4IflzrCL0zltt-2" target="IErN1is4IflzrCL0zltt-5">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="IErN1is4IflzrCL0zltt-2" value="&lt;font style=&quot;vertical-align: inherit;&quot;&gt;&lt;font style=&quot;vertical-align: inherit;&quot;&gt;Filas_completadas=0&lt;/font&gt;&lt;/font&gt;" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="345" y="-50" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IErN1is4IflzrCL0zltt-3" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="IrhKcL5lx_eICvQf7MEP-8" target="IErN1is4IflzrCL0zltt-1">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="405" y="-60" as="sourcePoint" />
            <mxPoint x="405" y="180" as="targetPoint" />
          </mxGeometry>
        </mxCell>
        <mxCell id="IErN1is4IflzrCL0zltt-4" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="IErN1is4IflzrCL0zltt-1" target="IErN1is4IflzrCL0zltt-2">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="IErN1is4IflzrCL0zltt-1" value="&lt;font style=&quot;vertical-align: inherit;&quot;&gt;&lt;font style=&quot;vertical-align: inherit;&quot;&gt;puntaje=0&lt;/font&gt;&lt;/font&gt;" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="345" y="-140" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IErN1is4IflzrCL0zltt-7" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="IErN1is4IflzrCL0zltt-5" target="IrhKcL5lx_eICvQf7MEP-11">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="IErN1is4IflzrCL0zltt-5" value="&lt;font style=&quot;vertical-align: inherit;&quot;&gt;&lt;font style=&quot;vertical-align: inherit;&quot;&gt;numero=0&lt;/font&gt;&lt;/font&gt;" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="345" y="50" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IErN1is4IflzrCL0zltt-8" value="&lt;font style=&quot;vertical-align: inherit;&quot;&gt;&lt;font style=&quot;vertical-align: inherit;&quot;&gt;&lt;font style=&quot;vertical-align: inherit;&quot;&gt;&lt;font style=&quot;vertical-align: inherit;&quot;&gt;Flas_completadas = numero&lt;/font&gt;&lt;/font&gt;&lt;/font&gt;&lt;/font&gt;" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="345" y="310" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IErN1is4IflzrCL0zltt-21" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="IErN1is4IflzrCL0zltt-11" target="IrhKcL5lx_eICvQf7MEP-2">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="IErN1is4IflzrCL0zltt-11" value="ESCRIBIR &quot;juego terminado su puntaje es:&quot;,puntaje" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;fixedSize=1;" vertex="1" parent="1">
          <mxGeometry x="302.5" y="830" width="205" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IErN1is4IflzrCL0zltt-19" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0;entryY=0.5;entryDx=0;entryDy=0;" edge="1" parent="1" target="IErN1is4IflzrCL0zltt-11">
          <mxGeometry relative="1" as="geometry">
            <mxPoint x="210" y="600" as="sourcePoint" />
            <mxPoint x="300" y="860" as="targetPoint" />
            <Array as="points">
              <mxPoint x="240" y="600" />
              <mxPoint x="240" y="860" />
            </Array>
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
ploading Diagrama TETRIS.drawio…]()

