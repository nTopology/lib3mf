# lib3mf

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} /wd4267")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} /wd4244")

#Common Folder

list (APPEND sources
"Source\Common\Math\NMR_PairMatchingTree.cpp"
"Source\Common\Math\NMR_Vector.cpp"
"Source\Common\Math\NMR_VectorTree.cpp"
"Source\Common\Math\NMR_Matrix.cpp"
	)

list (APPEND sources
"Source\Common\Mesh\NMR_MeshBuilder.cpp"
"Source\Common\Mesh\NMR_Mesh.cpp"
	)


list (APPEND sources
"Source\Common\MeshExport\NMR_MeshExportEdgeMap.cpp"
"Source\Common\MeshExport\NMR_MeshExporter.cpp"
"Source\Common\MeshExport\NMR_MeshExporter_STL.cpp"
	)


list (APPEND sources
"Source\Common\MeshImport\NMR_MeshImporter_STL.cpp"
"Source\Common\MeshImport\NMR_MeshImporter.cpp"
	)


list (APPEND sources
"Source\Common\MeshInformation\NMR_MeshInformation_NodeColors.cpp"
"Source\Common\MeshInformation\NMR_MeshInformation_TexCoords.cpp"
"Source\Common\MeshInformation\NMR_MeshInformationContainer.cpp"
"Source\Common\MeshInformation\NMR_MeshInformationFactory.cpp"
"Source\Common\MeshInformation\NMR_MeshInformationHandler.cpp"
"Source\Common\MeshInformation\NMR_MeshInformation.cpp"
"Source\Common\MeshInformation\NMR_MeshInformation_BaseMaterials.cpp"
	)

list (APPEND sources
"Source\Common\OPC\NMR_OpcPackageRelationshipReader.cpp"
"Source\Common\OPC\NMR_OpcPackageWriter.cpp"
"Source\Common\OPC\NMR_OpcPackagePart.cpp"
"Source\Common\OPC\NMR_OpcPackageReader.cpp"
"Source\Common\OPC\NMR_OpcPackageRelationship.cpp"
	)

list (APPEND sources
"Source\Common\Platform\NMR_ExportStream_Callback.cpp"
"Source\Common\Platform\NMR_ExportStream_ZIP.cpp"
"Source\Common\Platform\NMR_ImportStream_Memory.cpp"
"Source\Common\Platform\NMR_ImportStream_ZIP.cpp"
"Source\Common\Platform\NMR_PortableZIPWriter.cpp"
"Source\Common\Platform\NMR_PortableZIPWriterEntry.cpp"
"Source\Common\Platform\NMR_Time.cpp"
"Source\Common\Platform\NMR_XmlReader.cpp"
"Source\Common\Platform\NMR_XmlReader_Native.cpp"
"Source\Common\Platform\NMR_XmlWriter.cpp"
"Source\Common\Platform\NMR_XmlWriter_Native.cpp"
"Source\Common\Platform\NMR_ExportStream.cpp"
	)


list (APPEND sources
"Source\Common\NMR_Exception_Windows.cpp"
"Source\Common\NMR_StringUtils.cpp"
"Source\Common\NMR_Exception.cpp"
	)


#Model folder

list (APPEND sources
"Source\Model\Classes\NMR_ModelMetaData.cpp"
"Source\Model\Classes\NMR_ModelObject.cpp"
"Source\Model\Classes\NMR_ModelResource.cpp"
"Source\Model\Classes\NMR_ModelTexture2D.cpp"
"Source\Model\Classes\NMR_ModelThumbnail.cpp"
"Source\Model\Classes\NMR_Model.cpp"
"Source\Model\Classes\NMR_ModelBaseMaterial.cpp"
"Source\Model\Classes\NMR_ModelBaseMaterials.cpp"
"Source\Model\Classes\NMR_ModelBuildItem.cpp"
"Source\Model\Classes\NMR_ModelComponent.cpp"
"Source\Model\Classes\NMR_ModelComponentsObject.cpp"
"Source\Model\Classes\NMR_ModelDefaultProperty.cpp"
"Source\Model\Classes\NMR_ModelDefaultProperty_BaseMaterial.cpp"
"Source\Model\Classes\NMR_ModelDefaultProperty_Color.cpp"
"Source\Model\Classes\NMR_ModelDefaultProperty_TexCoord2D.cpp"
"Source\Model\Classes\NMR_ModelMeshObject.cpp"
	)


list (APPEND sources
"Source\Model\Reader\v093\NMR_ModelReaderNode093_Triangles.cpp"
"Source\Model\Reader\v093\NMR_ModelReaderNode093_Vertex.cpp"
"Source\Model\Reader\v093\NMR_ModelReaderNode093_Vertices.cpp"
"Source\Model\Reader\v093\NMR_ModelReaderNode093_Build.cpp"
"Source\Model\Reader\v093\NMR_ModelReaderNode093_BuildItem.cpp"
"Source\Model\Reader\v093\NMR_ModelReaderNode093_Color.cpp"
"Source\Model\Reader\v093\NMR_ModelReaderNode093_Component.cpp"
"Source\Model\Reader\v093\NMR_ModelReaderNode093_Components.cpp"
"Source\Model\Reader\v093\NMR_ModelReaderNode093_Material.cpp"
"Source\Model\Reader\v093\NMR_ModelReaderNode093_Mesh.cpp"
"Source\Model\Reader\v093\NMR_ModelReaderNode093_Object.cpp"
"Source\Model\Reader\v093\NMR_ModelReaderNode093_Resources.cpp"
"Source\Model\Reader\v093\NMR_ModelReaderNode093_Texture.cpp"
"Source\Model\Reader\v093\NMR_ModelReaderNode093_TextureVertex.cpp"
"Source\Model\Reader\v093\NMR_ModelReaderNode093_TextureVertices.cpp"
"Source\Model\Reader\v093\NMR_ModelReaderNode093_Triangle.cpp"
	)


list (APPEND sources
"Source\Model\Reader\v100\NMR_ModelReaderNode100_Tex2Coord.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_Tex2DGroup.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_Texture2D.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_Triangle.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_Triangles.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_Vertex.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_Vertices.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_BaseMaterial.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_BaseMaterials.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_Build.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_BuildItem.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_Color.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_Colors.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_Component.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_Components.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_Mesh.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_MetaData.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_Object.cpp"
"Source\Model\Reader\v100\NMR_ModelReaderNode100_Resources.cpp"
	)


list (APPEND sources
"Source\Model\Reader\NMR_ModelReader_TexCoordMapping.cpp"
"Source\Model\Reader\NMR_ModelReaderNode.cpp"
"Source\Model\Reader\NMR_ModelReaderNode_Model.cpp"
"Source\Model\Reader\NMR_ModelReaderWarnings.cpp"
"Source\Model\Reader\NMR_ModelReader.cpp"
"Source\Model\Reader\NMR_ModelReader_3MF.cpp"
"Source\Model\Reader\NMR_ModelReader_3MF_GCC.cpp"
"Source\Model\Reader\NMR_ModelReader_3MF_Native.cpp"
"Source\Model\Reader\NMR_ModelReader_3MF_OPC.cpp"
"Source\Model\Reader\NMR_ModelReader_ColorMapping.cpp"
"Source\Model\Reader\NMR_ModelReader_STL.cpp"
	)


list (APPEND sources
"Source\Model\Writer\v100\NMR_ModelWriterNode100_Model.cpp"
"Source\Model\Writer\v100\NMR_ModelWriterNode100_Mesh.cpp"

)


list (APPEND sources
"Source\Model\Writer\NMR_ModelWriter_TexCoordMapping.cpp"
"Source\Model\Writer\NMR_ModelWriter_TexCoordMappingContainer.cpp"
"Source\Model\Writer\NMR_ModelWriterNode.cpp"
"Source\Model\Writer\NMR_ModelWriter.cpp"
"Source\Model\Writer\NMR_ModelWriter_3MF.cpp"
"Source\Model\Writer\NMR_ModelWriter_3MF_Native.cpp"
"Source\Model\Writer\NMR_ModelWriter_3MF_OPC.cpp"
"Source\Model\Writer\NMR_ModelWriter_ColorMapping.cpp"
"Source\Model\Writer\NMR_ModelWriter_STL.cpp"
)


list (APPEND sources

)


add_library(lib3mf STATIC ${sources})

target_include_directories(lib3mf PUBLIC Include)