# Recuperacion_funcionalidad_puntaje_tetris

PSEUDOCODIGO
[UploadinAlgoritmo funcionalidad_puntuaje_tetris
	DEFINIR puntuaje COMO ENTERO;
	DEFINIR filas_completadas COMO ENTERO;
	puntuaje= 0;  
	ESCRIBIR "presione iniciar para empezar a ganar puntos";
	LEER puntuaje;
	SI puntuaje > 0 ENTONCES
	puntuaje = puntuaje * 100;	
	ESCRIBIR"puntos actuales:",puntuaje;
SiNo
	ESCRIBIR"no completo ninguna fila";
FinSI
FinAlgoritmo
g funcionalidad_puntuaje_tetris.psc…]()





DIAGRAMA DE FLUJO
[Uploadi<mxfile host="app.diagrams.net" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/134.0.0.0 Safari/537.36" version="26.1.1">
  <diagram name="Página-1" id="yz_0NU_y8Ucjf3_ebRbI">
    <mxGraphModel dx="1120" dy="1637" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
      <root>
        <mxCell id="0" />
        <mxCell id="1" parent="0" />
        <mxCell id="IrhKcL5lx_eICvQf7MEP-6" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="IrhKcL5lx_eICvQf7MEP-1" target="IrhKcL5lx_eICvQf7MEP-4">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-1" value="INICIO" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="330" y="-180" width="150" height="80" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-2" value="FIN" style="ellipse;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="360" y="780" width="120" height="80" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-7" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="IrhKcL5lx_eICvQf7MEP-4" target="IrhKcL5lx_eICvQf7MEP-5">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-4" value="&lt;font style=&quot;vertical-align: inherit;&quot;&gt;&lt;font style=&quot;vertical-align: inherit;&quot;&gt;DEFINIR puntaje COMO ENTERO&lt;/font&gt;&lt;/font&gt;" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="345" y="-60" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-10" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="IrhKcL5lx_eICvQf7MEP-5" target="IrhKcL5lx_eICvQf7MEP-8">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-5" value="&lt;font style=&quot;vertical-align: inherit;&quot;&gt;&lt;font style=&quot;vertical-align: inherit;&quot;&gt;DEFINIR filas_completadas COMO ENTERO&lt;/font&gt;&lt;/font&gt;" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="345" y="30" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-12" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="IrhKcL5lx_eICvQf7MEP-8" target="IrhKcL5lx_eICvQf7MEP-11">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-8" value="&lt;font style=&quot;vertical-align: inherit;&quot;&gt;&lt;font style=&quot;vertical-align: inherit;&quot;&gt;puntaje=0&lt;/font&gt;&lt;/font&gt;" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="345" y="110" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-14" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="IrhKcL5lx_eICvQf7MEP-11" target="IrhKcL5lx_eICvQf7MEP-13">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-11" value="ESCRIBIR&quot;presiona iniciar para empezar a ganar puntos&amp;nbsp; &quot;" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;fixedSize=1;" vertex="1" parent="1">
          <mxGeometry x="255" y="200" width="300" height="80" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-24" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;" edge="1" parent="1" source="IrhKcL5lx_eICvQf7MEP-13" target="IrhKcL5lx_eICvQf7MEP-15">
          <mxGeometry relative="1" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-13" value="LEER PUNTAJE" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;fixedSize=1;" vertex="1" parent="1">
          <mxGeometry x="345" y="310" width="120" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-16" value="SI" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="IrhKcL5lx_eICvQf7MEP-15">
          <mxGeometry x="0.1053" y="-5" relative="1" as="geometry">
            <mxPoint x="600" y="540" as="targetPoint" />
            <Array as="points">
              <mxPoint x="600" y="455" />
            </Array>
            <mxPoint x="5" y="-5" as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-17" value="NO" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="IrhKcL5lx_eICvQf7MEP-15">
          <mxGeometry x="-0.0658" y="-5" relative="1" as="geometry">
            <mxPoint x="240" y="540" as="targetPoint" />
            <Array as="points">
              <mxPoint x="241" y="455" />
            </Array>
            <mxPoint x="5" y="-5" as="offset" />
          </mxGeometry>
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-15" value="puntaje es &amp;gt; 0" style="rhombus;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="315" y="400" width="180" height="110" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-22" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;" edge="1" parent="1" source="IrhKcL5lx_eICvQf7MEP-18" target="IrhKcL5lx_eICvQf7MEP-2">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="230" y="820" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-18" value="No completo ninguna fila" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;fixedSize=1;" vertex="1" parent="1">
          <mxGeometry x="150" y="540" width="160" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-19" value="ESCRIBIR &quot;su puntaje es ,puntaje&quot;" style="shape=parallelogram;perimeter=parallelogramPerimeter;whiteSpace=wrap;html=1;fixedSize=1;" vertex="1" parent="1">
          <mxGeometry x="520" y="650" width="180" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-21" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;" edge="1" parent="1" source="IrhKcL5lx_eICvQf7MEP-20" target="IrhKcL5lx_eICvQf7MEP-19">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="600" y="610" />
              <mxPoint x="600" y="610" />
            </Array>
          </mxGeometry>
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-20" value="puntaje = puntaje * 100" style="rounded=0;whiteSpace=wrap;html=1;" vertex="1" parent="1">
          <mxGeometry x="540" y="540" width="140" height="60" as="geometry" />
        </mxCell>
        <mxCell id="IrhKcL5lx_eICvQf7MEP-23" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=1.008;entryY=0.613;entryDx=0;entryDy=0;entryPerimeter=0;" edge="1" parent="1" source="IrhKcL5lx_eICvQf7MEP-19" target="IrhKcL5lx_eICvQf7MEP-2">
          <mxGeometry relative="1" as="geometry">
            <Array as="points">
              <mxPoint x="610" y="820" />
              <mxPoint x="481" y="820" />
            </Array>
          </mxGeometry>
        </mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
ng Diagrama TETRIS.drawio…]()


